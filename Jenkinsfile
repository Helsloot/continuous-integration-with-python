pipeline {
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('Hello') {
            steps {
                sh 'python --version'
            }
        }
        stage('Test') {
            steps {
                sh 'py.test'
            }
        }
    }
}
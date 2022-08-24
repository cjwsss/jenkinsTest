pipeline {
    agent {
        docker { image 'python:3.9.13-alpine3.16' }
        reuseNode true
    }
    stages {
        stage('Test') {
            steps {
                sh 'python -V'
                sh 'python hello.py'
            }
        }
    }
}
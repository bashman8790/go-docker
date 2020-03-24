pipeline {
    agent {
        docker { image 'alpine:3.11.5' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'ls -al'
                sh 'pwd'
            }
        }
        stage('Build') {
            steps {
                sh 'docker build . -t go:1'
                sh 'docker images'
            }
        }
    }
}

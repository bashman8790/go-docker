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
    }
}

pipeline {
    agent {
        docker { image 'alpine' }
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

pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
                echo 'Hello world!' 
            }
            steps {
                ls -al
            }
        }
        stage('Stage 2') {
            steps {
                docker build -t go:1 . 
            }
        }
    }
}

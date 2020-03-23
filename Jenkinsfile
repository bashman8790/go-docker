node {

    stage('Initialize'){
	 sh "echo start"
	 sh "ls -al"
	 sh "pwd"
    }
    stage('Checkout'){
          checkout scm
     }
    stage('Build'){
        sh "docker build -t go:1 ."
    }
	
}

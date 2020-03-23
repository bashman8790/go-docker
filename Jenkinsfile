node {

    stage('Initialize'){
	 sh "echo start"
	 sh "ls -al"
	 sh "echo webhok add"
    }
    stage('Checkout'){
          checkout scm
     }
    stage('Build'){
        sh "bash build.sh"
    }
	
}

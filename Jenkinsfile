pipeline{
    agent { label 'go'}
    stages{
        stage('initial'){
            steps{
                echo "This is the start Pipeline"
            }
        }
	    stage('call another'){
		    steps{
		    	build Jenkinsfile-common
		    }
	    }
}
}

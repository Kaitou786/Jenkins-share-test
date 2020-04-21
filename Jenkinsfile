pipeline{
    agent { label 'jenkins-slave'}
    stages{
        stage('initial'){
            steps{
                echo "This is the start Pipeline"
            }
        }
	    stage('call another'){
		    steps{
		    	build 'Jenkinsfile-common'
		    }
	    }
}
}

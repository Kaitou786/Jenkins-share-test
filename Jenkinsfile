pipeline{
    agent                    { label 'jenkins-slave'}				//agent specifies where the pipeline will execute. 
    stages {
        stage ("build") {		//an arbitrary stage name
            steps {
               echo "this is different"	//this is where we specify which job to invoke.
            }
        }
    }
}

pipeline {	 
	agent any	
	tools {
		maven 'maven3'
		}
    	stages {     	 
    	stage("Compile") {          	 
            	steps {               	 
                	bat 'mvn --version'
			bat "mvn compile"          	 
            	}     	 
        	}     	 
    	stage("Unit test") {          	 
        	steps {               	 
                	bat "mvn test"          	 
            	}     	 
        	}	 
    	}
}

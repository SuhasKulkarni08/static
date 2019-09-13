pipeline {
    agent any
	    stages {
	    	stage('Stage1') {
	    	    steps {
	                sh ‘echo “Hello Worldas”’
	                sh ‘’’
	                    echo “Multiline shell steps work too”
			    ls -lah
			‘’’
	            }
	        }
	    }
	}

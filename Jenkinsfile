pipeline { 
   agent any 
      stages {
	  stage('build') { 
             steps { 
		     sh 'echo "Hello World"'
		     sh 'pwd'
		     sh '''
		       echo "Multiline steps test"
		       ls -lah
		     '''
		     
	     } 
	  } 
      } 
}

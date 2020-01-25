pipeline { 
   agent any 
      stages {
	  stage('Upload to AWS') { 
             steps { 
		     sh 'echo "Hello World"'
		     sh 'pwd'
		     sh '''
		       echo "Multiline steps test"
		       ls -lah
		     '''
		     withAWS(credentials: 'aws-static'){
		     	s3Upload bucket: 'jenkins-pipeline-udacity', includePathPattern: "*.html", workingDir: '.'
		     }
	     } 
	  } 
      } 
}

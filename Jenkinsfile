pipeline { 
   agent any 
      stages { 
	  stage('UploadToAWS') { 
             steps { 
		     sh 'echo "Hello World"'
		     sh 'pwd'
		     sh '''
		       echo "Multiline steps test"
		       ls -lah
		     '''
		     withAWS(credentials: 'aws-static') {
                         s3Upload bucket: 'jenkinsmahabucket', includePathPattern: "*.html", workingDir: '.'
                    }
	     } 
	  } 
      } 
}

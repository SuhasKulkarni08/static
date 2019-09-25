pipeline { 
   agent any 
      stages { 
	  stage('Build') { 
             steps { 
		     sh 'echo "Hello World"'
		     pwd
		     ls -lt
		     sh '''
		       echo "Multiline steps works too"
		       ls -lah
		     '''
		     withAWS(credentials: 'aws-static', region: 'us-west-1') {
                         s3Upload bucket: 'jenkinsmahabucket', includePathPattern: "*.html", workingDir: '.'
                    }
	     } 
	  } 
      } 
}

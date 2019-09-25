pipeline { 
   agent any 
      stages { 
	  stage('Build') { 
             steps { 
		     sh 'echo "Hello World"'
		     sh 'pwd'
		    sh 'ls -lt'
		     sh '''
		       echo "Multiline steps works too"
		       ls -lah
		     '''
		     withAWS(credentials: 'aws-static', region: 'us-west-2') {
                         s3Upload bucket: 'jenkinsmahabucket', includePathPattern: "*.html", workingDir: '.'
                    }
	     } 
	  } 
      } 
}

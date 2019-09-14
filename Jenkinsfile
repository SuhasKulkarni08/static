pipeline {
  agent any
    stages {
      stage('build') {
        steps {
	  script {
	    #!/bin/bash
	    env.SHCOM = echo 'HelloWorldsing'
	    echo '$BASH'
	    bash '-ci echo $PATH'
	    sh "${env.SHCOM}"

	  	}
	    }
	}
    }
}

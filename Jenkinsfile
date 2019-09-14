pipeline {
  agent any
    stages {
      stage('build') {
        steps {
	  script {
	    env.SHCOM = echo 'HelloWorldsing'
	    echo '$BASH'
	    sh "${env.SHCOM}"

	  	}
	    }
	}
    }
}

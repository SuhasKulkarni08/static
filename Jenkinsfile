pipeline {
  agent any
    stages {
      stage('build') {
        steps {
	  script {
	    env.SHCOM = echo 'HelloWorldsing'
	  	}
	  sh "${env.SHCOM}"
	    }
	}
    }
}

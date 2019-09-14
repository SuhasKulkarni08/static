pipeline {
  agent any
    stages {
      stage('build') {
        steps {
	  script {
	    env.SHCOM = echo 'HelloWorldsing'
	    bash '-ci echo $PATH'
	    sh "${env.SHCOM}"

	  	}
	    }
	}
    }
}

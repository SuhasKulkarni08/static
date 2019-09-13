pipeline {
  agent any
    stages {
      stage('build') {
        steps {
          sh ‘echo Hello Worldas’
	  script {
	    env.SHCOM = echo 'HelloWorldsing'
	  	}
	  sh "${env.SHCOM}"
	    }
	}
    }
}

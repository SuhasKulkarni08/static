pipeline {
  agent any
    stages {
      stage('build') {
        steps {
	  script {
	    env.SHCOM = echo 'HelloWorldsing'
	    export PS1=1
	    bash -ci 'echo $PATH'
	    sh "${env.SHCOM}"

	  	}
	    }
	}
    }
}

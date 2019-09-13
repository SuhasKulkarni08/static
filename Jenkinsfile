pipeline {
    agent any
    node('master', {
        echo 'env.PATH=' + env.PATH
        sh('env')
   }
    stages {
    	stage('Stage1') {
    	    steps {
                sh 'echo 'Hello Worldas''
            }
        }
    }
}

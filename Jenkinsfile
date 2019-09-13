pipeline {
    node {
        echo 'env.PATH=' + env.PATH
        sh('env')
         agent any
            stages {
                stage('Stage1') {
                    steps {
                        sh 'echo 'Hello Worldas''
                    }
                }
            }
         }
   
      }

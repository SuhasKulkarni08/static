pipeline {
    agent { 
        node {
            stages {
                stage('Build') {
                     echo 'env.PATH=' + env.PATH
                     sh('env')
                    }
                }
            }
          }
}

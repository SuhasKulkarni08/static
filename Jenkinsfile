pipeline {
    agent { 
        node {
            stages {
                stage('Stage1') {
                     echo 'env.PATH=' + env.PATH
                     sh('env')
                    }
                }
            }
          }
}

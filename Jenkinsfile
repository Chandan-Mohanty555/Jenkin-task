pipeline {
    agent { label 'agent1' }
    stages {
        stage('Parallel Execution') {
            parallel {
                stage('Stage 1') {
                    steps {
                        echo 'Running Stage 1'
                    }
                }
                stage('Stage 2') {
                    steps {
                        echo 'Running Stage 2'
                    }
                }
            }
        }
      stage('This is general stage') 
       {  
         steps 
         {
             echo 'this is general stage o/p '
         }


       }

    }
}

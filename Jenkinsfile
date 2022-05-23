pipeline{
   agent {
       node {
           label 'ansible'
       }
   }

   environment {
     DEMO_URL= "google.com"
     SSH=credentials("SSH")
   }
    stages {
        stage('Test'){
         environment{
           DEMO_URL="yahoo.com"
         }
          steps {
            echo 'Hello World'
            echo DEMO_URL
          }
        }

    stage('Test1'){
              steps {
                echo 'Hello World'
              }
       }
    }
}
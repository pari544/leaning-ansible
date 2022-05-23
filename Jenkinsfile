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
pipeline {
   agent any

   stages {
      stage('Start') {
         steps {
            echo 'First Stage'
         }
      }
      stage('msi-install') {
         steps {
            bat "install-msi.bat"
         }  
      }
   }
}

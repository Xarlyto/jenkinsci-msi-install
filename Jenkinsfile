pipeline {
   agent any

   stages {
      stage('Start') {
         steps {
            echo 'Hello World'
         }
      }
      stage('msi-install') {
         steps {
            bat "msiexec /i 'D:/desarrollo/programas/putty-0.73-installer.msi'"
         }      
   }
}

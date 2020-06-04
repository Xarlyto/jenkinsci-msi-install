pipeline {
   agent any

   stages {
      stage('msi-uninstall') {
         steps {
            echo 'Try to delete if is installed'
            bat "uninstall-msi.bat"
         }
      }
      stage('msi-install') {
         steps {
            echo 'Install msi'
            bat "install-msi.bat"
         }  
      }
   }
}

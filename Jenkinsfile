pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        bat(script: '%sourceDir%/create_build.bat', label: 'Declarative : Checkout')
      }
    }

  }
  environment {
    sourceDir = 'C:\\Apps\\jenkins\\workspace\\SCM_BlueOcean'
    targetTag = '202022220'
  }
}
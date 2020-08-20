pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        sh '%sourceDir%/create_build.bat --targetTag=%targetTag%'
      }
    }

  }
  environment {
    sourceDir = 'C:\\Apps\\jenkins\\workspace\\SCM_BlueOcean'
    targetTag = '202022220'
  }
}
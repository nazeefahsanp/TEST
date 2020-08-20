pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        bat(script: '%sourceDir%/create_build.bat --targetTag=%targetTag%', label: '<h1>Checkout</h1>')
      }
    }

  }
  environment {
    sourceDir = 'C:\\Apps\\jenkins\\workspace\\SCM_BlueOcean'
    targetTag = '202022220'
  }
}
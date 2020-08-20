pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        node(label: 'Checkout') {
          bat(script: '%sourceDir%/create_build.bat --targetTag=%targetTag%', label: 'Checkout')
        }

      }
    }

  }
  environment {
    sourceDir = 'C:\\Apps\\jenkins\\workspace\\SCM_BlueOcean'
    targetTag = '202022220'
  }
}
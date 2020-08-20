pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        bat(script: '%sourceDir%/create_build.bat --targetTag=%targetTag%', label: 'Declarative : Checkout')
        bat 'labelledBatch label: \'Building the universe from scratch...\', script: """     echo "Sparking the Big Bang..."     echo "Cosmic inflation begins..."'
      }
    }

  }
  environment {
    sourceDir = 'C:\\Apps\\jenkins\\workspace\\SCM_BlueOcean'
    targetTag = '202022220'
  }
}
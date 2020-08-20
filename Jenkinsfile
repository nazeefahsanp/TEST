pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        bat(script: ' @echo off echo "Checkout" %sourceDir%/create_build.bat --branchName=%branchName% --targetTag=%targetTag% --originTag="%originTag%" --sourceDir=%sourceDir%', label: 'Checkout', returnStdout: true)
      }
    }

  }
  environment {
    sourceDir = 'C:\\Apps\\jenkins\\workspace\\SCM_BlueOcean'
  }
}
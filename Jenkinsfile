pipeline {
  agent any
  stages {
    stage('Declarative : Checkout') {
      steps {
        bat(script: ' @echo off echo "Checkout"  @%sourceDir%/create_build.bat --branchName=%branchName% --targetTag=%targetTag% --originTag="%originTag%" --sourceDir=%sourceDir%', label: 'Declarative : Checkout')
      }
    }

  }
  environment {
    sourceDir = 'C:\\Apps\\jenkins\\workspace\\SCM_BlueOcean'
  }
}
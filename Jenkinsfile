pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        bat(script: ' %sourceDir%/create_build.bat --branchName=%branchName% --targetTag=%targetTag% --originTag="%originTag%" --sourceDir=%sourceDir%', label: 'Checkout')
      }
    }

  }
}
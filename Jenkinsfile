pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        build 'Source Code Analysis'
      }
    }

  }
  environment {
    sourceDir = 'C:\\Apps\\jenkins\\workspace\\SCM_BlueOcean'
    targetTag = '202022220'
  }
}
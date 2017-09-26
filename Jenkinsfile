pipeline {
  agent any
  stages {
    stage('Cake Build') {
      steps {
        powershell(script: './build.ps1', returnStatus: true, returnStdout: true)
      }
    }
  }
}
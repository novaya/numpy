pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        bat(script: 'python runtests.py', returnStatus: true, returnStdout: true)
        sh 'python3 --version'
      }
    }

  }
}
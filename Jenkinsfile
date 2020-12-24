pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        sh 'python3 --version'
        bat(script: 'python runtests.py', returnStatus: true, returnStdout: true)
      }
    }

  }
}
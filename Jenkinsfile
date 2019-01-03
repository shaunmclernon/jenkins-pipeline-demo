pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        sh 'node --version'
        echo 'Hello world'
      }
    }
    stage('Build') {
      steps {
        catchError() {
          echo 'Child'
        }

      }
    }
  }
}
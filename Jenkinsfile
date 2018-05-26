pipeline {
  agent any
  stages {
    stage('Compile') {
      steps {
        sh 'make'
      }
    }
    stage('Test') {
      steps {
        sh 'make test'
      }
    }
  }
}
pipeline {
  agent {
    node {
      label 'Jenkins_slave_linux'
    }

  }
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
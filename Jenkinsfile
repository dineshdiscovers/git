pipeline {
  agent {
    node {
      label 'Jenkins_slaves'
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
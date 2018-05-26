pipeline {
  agent {
    node {
      label 'LinuxSlave'
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
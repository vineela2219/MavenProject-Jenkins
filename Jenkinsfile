pipeline {
  agent {
    docker { image 'python:3' }
  }
  stages {
    stage('Test') {
      steps {
        sh 'python3 --version'
      }
    }
    stage('Test2') {
      steps {
        sh 'python3 test.py'
      }
    }
  }
}

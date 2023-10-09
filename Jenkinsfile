pipeline {
  agent {
    docker { image 'python:3.8' }
  }
  stages {
    stage('Test') {
      steps {
        sh 'python3 --version'
      }
    }
  }
    stage('Test2') {
      steps {
        sh 'print("Hello World")'
      }
    }
}

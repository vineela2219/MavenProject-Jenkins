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
  stages {
    stage('Test2') {
      steps {
        sh 'print("Hello World")'
      }
    }
  }
}

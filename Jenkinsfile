pipeline {
  agent any
  stages {
    stage('Say Hello') {
      steps {
        echo 'Hello Frank'
        sh 'java -version'
      }
    }
  }
  environment {
    MY_NAME = 'Mary'
  }
}
pipeline {
  agent {
    label 'jdk9'
  }
  stages {
    stage('Say Hello') {
      steps {
        echo 'Hello Frank'
        sh 'java -version'
      }
    }
  }
}
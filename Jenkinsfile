pipeline {
  agent {
    label 'jdk8'
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
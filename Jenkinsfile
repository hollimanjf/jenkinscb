pipeline {
  agent any
  stages {
    stage('Say Hello') {
      steps {
        echo 'Hello Frank'
        sh '''pipeline {
   agent any
   stages {
      stage(\'Say Hello\') {
         steps {
            echo \'Hello World!\'   
            sh \'java -version\'
         }
      }
   }
}'''
        }
      }
    }
  }
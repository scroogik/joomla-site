pipeline {
  agent any
  stages {
    stage('Message') {
      steps {
        echo 'Hello world!'
        sh 'tidy -q -e index.html'
      }
    }

  }
}
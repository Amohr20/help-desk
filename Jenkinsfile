pipeline {
  agent any
  stages {
    stage('verify version') {
      steps {
        sh 'php --version'
      }
    }
    stage('index') {
      steps {
        sh 'php index.php'
      }
    }
  }
}

pipeline {
  agent any
  stages {
    stage('init') {
      steps {
        sh 'chmod +x gradlew'
      }
    }
    stage('clean') {
      steps {
        sh 'gralew clean'
      }
    }
  }
}
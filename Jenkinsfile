pipeline {
  agent {
    node {
      label 'init'
    }
    
  }
  stages {
    stage('init') {
      steps {
        sh 'chmod +x gradlew'
      }
    }
  }
}
pipeline {
  agent {
    node {
      label 'docker'
    }
    
  }
  stages {
    stage('error') {
      steps {
        sh '''./gradlew clean
./gradlew assemble'''
      }
    }
  }
}
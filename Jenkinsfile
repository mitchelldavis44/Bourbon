pipeline {
  agent {
    node {
      label 'docker'
    }
    
  }
  stages {
    stage('') {
      steps {
        sh '''./gradlew clean
./gradlew assemble'''
      }
    }
  }
}
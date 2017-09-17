pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        bat(script: 'mvnw clean install', encoding: 'UTF-8', returnStdout: true, returnStatus: true)
      }
    }
  }
}
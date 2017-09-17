pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        bat(script: 'mvn clean install', encoding: 'UTF-8', returnStdout: true, returnStatus: true)
      }
    }
  }
}
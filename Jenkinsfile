pipeline {
  agent none
  stages {
    stage('Build') {
      agent any
      steps {
        sh 'sh \'mvn clean compile\''
      }
    }
  }
}
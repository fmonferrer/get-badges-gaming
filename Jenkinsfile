pipeline {
  agent none
  stages {
    stage('Build') {
      agent any
      steps {
        build 'mvn clean compile'
      }
    }
  }
}
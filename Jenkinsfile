pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat(script: 'ant clean compile', encoding: 'utf-8')
      }
    }
  }
}
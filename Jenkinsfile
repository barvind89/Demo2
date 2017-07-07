pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat(script: 'ant clean compile', encoding: 'utf-8')
      }
    }
    stage('Test') {
      steps {
        echo 'Test phase'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploying application'
      }
    }
  }
}
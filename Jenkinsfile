pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat(script: 'ant clean jar', encoding: 'utf-8')
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
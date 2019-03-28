pipeline {
  agent any
  stages {
    stage('Begin') {
      steps {
        echo 'Starting Pipeline'
      }
    }
    stage('Clone SCM') {
      steps {
        echo 'Cloning SCM'
        sh 'echo Hello World'
      }
    }
    stage('Build') {
      steps {
        echo 'Building'
        sh 'ps aux'
      }
    }
  }
}
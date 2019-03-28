pipeline {
  agent any
  stages {
    stage('Begin') {
      steps {
        timestamps() {
          echo 'Starting Pipeline'
        }

      }
    }
    stage('Clone SCM') {
      steps {
        timestamps() {
          sh 'echo Hello World'
          echo 'Cloning SCM'
        }

      }
    }
    stage('Build') {
      steps {
        timestamps() {
          sh 'ps aux'
          echo 'Building'
        }

      }
    }
  }
}
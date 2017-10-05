pipeline {
  agent any
  stages {
    stage('print') {
      steps {
        sh 'echo Hello World'
      }
    }
    stage('print1') {
      steps {
        echo 'Newstage2'
      }
    }
    stage('print2') {
      steps {
        sh 'echo Hi'
      }
    }
  }
}
pipeline {
  agent any
  stages {
    stage('Buzz Build') {
      steps {
        echo 'Build the Buzz application here'
      }
    }
    stage('Buzz Unit tests') {
      steps {
        echo 'Run unit tests'
      }
    }
    stage('Buzz regression tests') {
      steps {
        echo 'Run regression tests'
        echo 'Publish XML tests to JUnit'
        echo 'Send email notifications if the test fail '
      }
    }
  }
}
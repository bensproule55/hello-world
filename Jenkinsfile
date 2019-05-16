pipeline {
  agent any
  stages {
    stage('Check-in') {
      steps {
        sleep 5
        echo 'Good nap!'
        readFile 'README.md'
      }
    }
    stage('All done') {
      steps {
        echo 'Success'
      }
    }
  }
}
pipeline {
  agent any
  stages {
    stage('Check-in') {
      parallel {
        stage('Check-in') {
          steps {
            sleep 5
            echo 'Good nap!'
          }
        }
        stage('Error Handling') {
          steps {
            fileExists 'README.md'
            readFile(file: 'README', encoding: 'md')
          }
        }
      }
    }
    stage('All done') {
      steps {
        echo 'Success'
      }
    }
  }
}
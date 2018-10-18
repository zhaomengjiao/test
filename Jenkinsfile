pipeline {
  agent any
  stages {
    stage('prepare') {
      parallel {
        stage('prepare') {
          steps {
            echo 'preparing...'
          }
        }
        stage('build') {
          steps {
            echo 'building...'
          }
        }
      }
    }
    stage('end') {
      steps {
        echo 'finishing..'
      }
    }
  }
}
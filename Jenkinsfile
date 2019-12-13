pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building '
        sh 'jenkins/scripts/deliver.sh'
      }
    }

    stage('Test') {
      steps {
        echo 'Testing'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploying'
      }
    }

  }
}
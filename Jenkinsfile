pipeline {
  agent any
  stages {
    stage('login') {
      steps {
        echo 'login'
        sleep 2
      }
    }

    stage('test') {
      steps {
        echo 'test'
        sh 'date'
      }
    }

    stage('deploy') {
      steps {
        echo 'deploy'
      }
    }

  }
}
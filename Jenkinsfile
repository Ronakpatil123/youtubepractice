pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'pwd'
      }
    }

    stage('Testing') {
      parallel {
        stage('Testing') {
          steps {
            echo 'test step'
          }
        }

        stage('test parallel') {
          steps {
            echo 'parallel test'
          }
        }

      }
    }

    stage('Deployement usoong docker ') {
      steps {
        echo 'docker deployement '
      }
    }

  }
}
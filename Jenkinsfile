pipeline {
  agent any
  stages {
    stage('devlopment') {
      steps {
        echo 'This is development '
      }
    }

    stage('Test') {
      steps {
        echo 'This is Test'
      }
    }

    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'This is Build'
          }
        }

        stage('fixes') {
          steps {
            echo 'This is fixes'
          }
        }

        stage('operation ') {
          steps {
            echo 'This is operation '
          }
        }

        stage('Production ') {
          steps {
            echo 'This is Production '
          }
        }

        stage('Deployment') {
          steps {
            echo 'This is Deployment '
          }
        }

      }
    }

  }
}
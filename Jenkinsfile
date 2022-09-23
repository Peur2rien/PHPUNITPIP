pipeline {
  agent any
  stages {
    stage('Dev') {
      steps {
        echo 'TU'
      }
    }

    stage('Test Unitaire ') {
      parallel {
        stage('Test Unitaire ') {
          steps {
            echo 'TU'
          }
        }

        stage('Test Non Regression (TNR)') {
          steps {
            echo 'TNR'
          }
        }

      }
    }

    stage('Pre-Prod') {
      steps {
        echo 'Pre-Prod'
      }
    }

    stage('Production (Deploiment)') {
      steps {
        echo 'Production'
      }
    }

  }
}
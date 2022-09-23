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

    stage('SonarScanner') {
      steps {
        echo 'Pre-Prod'
      }
    }

    stage('Pre-Prod') {
      steps {
        echo 'Production'
      }
    }

    stage('Production') {
      steps {
        echo 'PROD'
      }
    }

  }
}
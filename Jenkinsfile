pipeline {
  agent any
  stages {
    stage('Browser Tests') {
      parallel {
        stage('Firefox') {
          steps {
            echo 'Firefox Tests'
          }
        }

        stage('Chrome') {
          steps {
            echo 'Chrome Tests'
          }
        }

      }
    }

  }
}
pipeline {
  agent any
  stages {
    stage('Fluffy Build') {
      parallel {
        stage('Fluffy Build') {
          steps {
            echo 'Placeholder'
            sh 'echo Another Placeholder'
          }
        }

        stage('Fluffy Test') {
          steps {
            sh 'sleep 5'
            sh 'echo Success!'
          }
        }

        stage('Fluffy Deploy') {
          steps {
            echo 'Placeholder'
          }
        }

      }
    }

  }
}
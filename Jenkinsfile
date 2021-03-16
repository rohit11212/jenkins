pipeline {
  agent any
  stages {
    stage('test') {
      parallel {
        stage('test') {
          steps {
            echo 'Hii'
          }
        }

        stage('Failed') {
          steps {
            echo 'Bye'
          }
        }

      }
    }

    stage('done') {
      steps {
        echo 'Done'
      }
    }

  }
}
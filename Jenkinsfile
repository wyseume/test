pipeline {
  agent any
  stages {
    stage('stage 1') {
      parallel {
        stage('stage 1') {
          steps {
            sh 'echo "hello"'
            echo 'haha'
          }
        }

        stage('stage 1_2') {
          steps {
            sh 'ehco "world"'
          }
        }

      }
    }

  }
}
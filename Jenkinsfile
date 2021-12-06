pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            sh 'echo test 1'
            sh 'echo step2'
          }
        }

        stage('') {
          steps {
            echo 'gggg'
          }
        }

      }
    }

    stage('Test') {
      steps {
        echo 'Test'
      }
    }

  }
}
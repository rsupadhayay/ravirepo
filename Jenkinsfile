pipeline {
  agent any
  stages {
    stage('test_stage') {
      parallel {
        stage('test_stage') {
          steps {
            echo 'test stage'
          }
        }

        stage('te') {
          agent {
            node {
              label 'host'
            }

          }
          steps {
            sleep 5
          }
        }

        stage('st3') {
          steps {
            echo 'hello'
          }
        }

      }
    }

  }
}
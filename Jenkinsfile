pipeline {
  agent any
  stages {
    stage('download') {
      parallel {
        stage('download') {
          steps {
            echo 'downloded'
          }
        }

        stage('parallel') {
          steps {
            echo 'build'
          }
        }

      }
    }

    stage('build') {
      steps {
        echo 'build'
        echo 'build'
      }
    }

    stage('test') {
      steps {
        echo 'test'
      }
    }

    stage('deploy') {
      steps {
        echo 'delivery'
      }
    }

  }
}
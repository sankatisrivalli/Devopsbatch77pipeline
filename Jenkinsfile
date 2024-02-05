pipeline {
  agent any
  stages {
    stage('Dev') {
      parallel {
        stage('Dev') {
          steps {
            echo 'Development stage'
          }
        }

        stage('test') {
          steps {
            echo 'testing stages'
          }
        }

        stage('plugin') {
          steps {
            echo 'plugin stage'
          }
        }

      }
    }

    stage('QA') {
      steps {
        echo 'QA stage'
      }
    }

    stage('UAT') {
      steps {
        echo 'UAT stage'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploy stage'
      }
    }

    stage('Operate') {
      steps {
        echo 'operate stage'
      }
    }

  }
}
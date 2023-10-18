pipeline {
  agent any
  stages {
    stage('dev') {
      parallel {
        stage('dev') {
          steps {
            echo 'dev stage'
          }
        }

        stage('test') {
          steps {
            echo 'testing stage'
          }
        }

        stage('pluggin') {
          steps {
            echo 'pluggin stage'
          }
        }

      }
    }

    stage('qa') {
      steps {
        echo 'qa stage'
      }
    }

    stage('uat') {
      steps {
        echo 'uat stage'
      }
    }

    stage('deploy') {
      steps {
        echo 'deploy stage'
      }
    }

    stage('oprate') {
      steps {
        echo 'operation stage'
      }
    }

  }
}
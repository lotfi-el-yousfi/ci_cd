pipeline {
  agent any
  stages {
    stage('') {
      steps {
        sh '''
pipeline {
    agent any

    stages {
        stage(\'Checkout\') {
            steps {
                echo \'Checking out project...\'
            }
        }

        stage(\'Build\') {
            steps {
                echo \'Building application...\'
            }
        }

        stage(\'Test\') {
            steps {
                echo \'Running tests...\'
            }
        }

        stage(\'Deploy\') {
            steps {
                echo \'Deploying application...\'
            }
        }
    }
}
'''
      }
    }

  }
}
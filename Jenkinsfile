pipeline {
    agent any
    stages {
      stage('Commit stage') {
        steps {
          sh '''
            echo Compiling
            sleep 2

            echo 'Running unit tests'
            sleep 2
          '''
        }
      }

      stage('Test') {
        steps {
          shell(
          '''
            echo 'Running component tests'
            ls -R
            sleep 2
          '''
          )

          sh '''
            echo 'Running1 component tests'
            sleep 1
          '''
        }
      }

      stage('Deploy') {
        steps {
          sh '''
            echo 'Deploy to environment'
            sleep 2
          '''
        }
      }
    }
}

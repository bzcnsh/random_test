pipeline {
    agent any
    stages {
      stage 'Commit stage' {
        echo 'Compiling'
        sleep 2

        echo 'Running unit tests'
        sleep 2
      }

      stage 'Test'
        echo 'Running component tests'
        sleep 2

      stage 'Deploy' {
        echo 'Deploy to environment'
        sleep 2
      }
    }
}

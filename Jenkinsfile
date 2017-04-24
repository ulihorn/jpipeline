pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building..'
        sleep 4
      }
    }
    stage('Test') {
      steps {
        parallel(
          "Test": {
            echo 'Testing..'
            sleep 3
            
          },
          "Test2": {
            echo 'Testing .. 2'
            sleep 5
            
          }
        )
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploying....'
      }
    }
  }
}
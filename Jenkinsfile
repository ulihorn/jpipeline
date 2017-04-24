pipeline {
  agent {
    docker {
      image 'maven:3.3.9-jdk-8'
      args '-v /home/uli/.m2:/root/.m2'
    }
    
  }
  stages {
    stage('Initialize') {
      steps {
        sh '''echo PATH = ${PATH}





'''
      }
    }
  }
}
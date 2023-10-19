pipeline {
  agent any
  stages {
    stage('buzz buzz') {
      steps {
        sh 'echo My nane is $BUSY_BEE'
      }
    }

    stage('bee bee') {
      steps {
        echo 'perrperrperr'
        echo 'zzzzzzzb'
      }
    }

    stage('Deploy to stage') {
      steps {
        input 'Deploy to stage?'
      }
    }

  }
  environment {
    BUSY_BEE = 'Working Bee'
  }
}
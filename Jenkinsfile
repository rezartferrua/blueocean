pipeline {
  agent none
  stages {
    stage('buzz buzz') {
      agent any
      steps {
        sh 'echo My nane is $BUSY_BEE'
      }
    }

    stage('bee bee') {
      agent any
      steps {
        echo 'perrperrperr'
        echo 'zzzzzzzb'
      }
    }

  }
  environment {
    BUSY_BEE = 'Working Bee'
  }
}
pipeline {
  agent none
  stages {
    stage('buzz buzz') {
      agent {
        label 'bzezezzz'
      }
      steps {
        sh 'echo My nane is $BUSY_BEE'
      }
    }

    stage('bee bee') {
      agent {
        label 'bzzzz'
      }
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
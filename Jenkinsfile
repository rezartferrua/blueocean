pipeline {
  agent none
  stages {
    stage('buzz buzz') {
      agent any
      steps {
        sh '''sudo mkdir ./target
sudo touch ./target/dummy.dum'''
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

    stage('Confirm Deploy to Staging') {
      steps {
        input 'Deploy to stage?'
      }
    }

  }
  environment {
    BUSY_BEE = 'Working Bee'
  }
  options {
    preserveStashes()
  }
}
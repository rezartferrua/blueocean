pipeline {
  agent none
  stages {
    stage('buzz buzz') {
      agent any
      steps {
        sh '''sudo mkdir ./target
sudo touch ./target/dummy.dum'''
        sh 'echo My nane is $BUSY_BEE'
        stash(name: 'stashed_filess', includes: 'target/**')
      }
    }

    stage('bee bee') {
      agent any
      steps {
        echo 'perrperrperr'
        echo 'zzzzzzzb'
        unstash 'stashed_filess'
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
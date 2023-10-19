pipeline {
  agent none
  stages {
    stage('buzz buzz') {
      agent any
      steps {
        sh '''sudo mkdir ./target
sudo touch ./target/dummy'''
        sh 'echo My nane is $BUSY_BEE'
        stash(name: 'stashed_files', includes: 'target/**')
      }
    }

    stage('bee bee') {
      agent any
      steps {
        echo 'perrperrperr'
        echo 'zzzzzzzb'
        unstash 'stashed_files'
      }
    }

  }
  environment {
    BUSY_BEE = 'Working Bee'
  }
}
pipeline {
  agent none
  stages {
    stage('buzz buzz') {
      agent any
      steps {
        sh 'echo My nane is $BUSY_BEE'
        stash(name: 'stashed_files', includes: 'target/**')
      }
    }

    stage('bee bee') {
      agent any
      steps {
        echo 'perrperrperr'
        echo 'zzzzzzzb'
        stash(name: 'more_stashed_files', includes: 'target/**')
      }
    }

  }
  environment {
    BUSY_BEE = 'Working Bee'
  }
}
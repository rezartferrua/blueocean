pipeline {
  agent any
  stages {
    stage('buzz buzz') {
      steps {
        sh 'echo My nane is $BUSY_BEE'
      }
    }

    stage('bee bee') {
      post {
        success {
          archiveArtifacts 'target/*.jar'
          stash(name: 'Java 7', includes: 'target/**')
        }

      }
      steps {
        echo 'perrperrperr'
        echo 'zzzzzzzb'
      }
    }

    stage('Deploy to stage') {
      when {
        branch 'master'
      }
      steps {
        input 'Deploy to stage?'
      }
    }

  }
  environment {
    BUSY_BEE = 'Working Bee'
  }
}
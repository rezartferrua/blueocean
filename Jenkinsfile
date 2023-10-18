pipeline {
  agent any
  stages {
    stage('buzz buzz') {
      steps {
        echo 'bzzzzzzzz'
        archiveArtifacts(artifacts: 'target/*.jar', fingerprint: true)
      }
    }

    stage('bee bee') {
      steps {
        echo 'perrperrperr'
        echo 'zzzzzzzb'
      }
    }

  }
}
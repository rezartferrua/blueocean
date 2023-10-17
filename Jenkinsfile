pipeline {
  agent any
  stages {
    stage('Buzz Build') {
      steps {
        sh '/var/lib/jenkins/sh/build.sh'
      }
    }

    stage('Buzz Test') {
      steps {
        sh '/var/lib/jenkins/sh/test-all.sh'
      }
    }

  }
}
pipeline {
  agent any
  stages {
    stage('Buzz Build') {
      steps {
        sh '/home/rezart/Downloads/training-core-fundamentals-sample-1/jenkins/build.sh'
      }
    }

    stage('Buzz Test') {
      steps {
        sh '/home/rezart/Downloads/training-core-fundamentals-sample-1/jenkins/test-all.sh'
      }
    }

  }
}
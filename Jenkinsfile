pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        echo 'test repo'
      }
    }
    stage('check') {
      steps {
        sleep 20
        sh printenv
        sh pwd
      }
    }
  }
}

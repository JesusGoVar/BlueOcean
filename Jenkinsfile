pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        svn 'http://10.61.241.43/repos/prueba'
      }
    }
    stage('Deploy Des') {
      steps {
        sh 'sh demo.sh'
      }
    }
  }
}
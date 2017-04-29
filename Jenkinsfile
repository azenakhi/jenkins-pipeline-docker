pipeline {
  agent { docker 'nginx:latest' }
  stages {
    stage('Test') {
      steps {
        sh 'ls'
      }
    }
    stage('Install') {
      steps {
        sh 'echo'
      }
    }
  }
  post {
    always {
      echo 'hello world'
    }
  }
}

pipeline {
  agent any
  stages {
    stage('Print Message') {
      steps {
        echo 'Hey jQuery is cloned.  Yay!!!'
      }
    }
    stage('Install Node Modules') {
      steps {
        powershell 'npm install'
      }
    }
  }
}
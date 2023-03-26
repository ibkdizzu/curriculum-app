pipeline {
  agent any
  stages {
    stage('checkout code') {
      steps {
        git(url: 'https://github.com/ibkdizzu/demo-app', branch: 'dev')
        git(url: 'https://github.com/ibkdizzu/demo-app/blob/dev/Jenkinsfile', branch: 'dev')
      }
    }

  }
}
pipeline {
  agent any
  stages {
    stage('checkout code') {
      steps {
        git(url: 'https://github.com/ibkdizzu/demo-app', branch: 'dev')
      }
    }
  stage('Log') {
    steps {
      sh 'ls -la'
    }
  }

  stage('Build') {
    steps {
      sh 'docker build -f curriculum-front/Dockerfile -t fuze365/curriculum-front:latest .'
    }
  }
  }
}

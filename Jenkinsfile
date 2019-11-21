pipeline {
  agent {
    node {
      label 'Windows'
    }

  }
  stages {
    stage('Source') {
      steps {
        git 'https://github.com/microsoft/vcpkg'
      }
    }

  }
  environment {
    COMPLETED_MSG = 'Build done!'
  }
}
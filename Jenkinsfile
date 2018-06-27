pipeline {
  agent any
  stages {
    stage('Colorize output') {
      steps {
        ansiColor(colorMapName: 'xterm')
      }
    }
    stage('git checkout') {
      steps {
        git(url: 'https://github.com/Libeccio84/jenkins.git', branch: 'master', poll: true)
      }
    }
  }
}
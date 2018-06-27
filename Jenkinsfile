pipeline {
  agent any
  stages {
    stage('git checkout') {
      steps {
        ansiColor(colorMapName: 'xterm') {
          git(url: 'https://github.com/Libeccio84/jenkins.git', branch: 'master', poll: true)
        }

      }
    }
  }
}
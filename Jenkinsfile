pipeline {
  agent any
  stages {
    stage('jenkinfile') {
      parallel {
        stage('jenkinfile') {
          steps {
            git 'https://github.com/DuHuy/duan.github.io.git'
          }
        }

        stage('') {
          steps {
            git(url: 'https://github.com/DuHuy/duan.github.io.git', branch: 'jenkinfile', changelog: true)
          }
        }

      }
    }

  }
}
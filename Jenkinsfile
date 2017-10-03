pipeline {
  agent any
  stages {
    stage('Pull') {
      steps {
        git(url: 'https://github.com/andrew-anguiano/acf-focal_point.git', branch: 'master', poll: true)
      }
    }
  }
}
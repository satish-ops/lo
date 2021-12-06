pipeline {
  agent any
  stages {
    stage('') {
      steps {
        echo 'hey'
      }
    }

    stage('testing') {
      steps {
        echo 'testing'
      }
    }

    stage('deploy') {
      when {
        branch 'main'
      }
      steps {
        echo 'deploy'
      }
    }

  }
}

pipeline {
  agent any
  stages {
    stage('') {
      steps {
        sh "print env | sort"
      }
    }

    stage('testing') {
      steps {
        echo " a = ${env.BUILD_URL}"
        sh 'echo build_number =a'
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

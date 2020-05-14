pipeline {
  agent any
  stages {
    stage('Development') {
      steps {
        echo ' echo "Multiline shell steps works too"                      ls -lah'
      }
    }

    stage('Staging') {
      steps {
        sh 'sh \'tidy -q -e *.html\''
      }
    }

  }
}
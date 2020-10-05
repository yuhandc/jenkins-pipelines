pipeline {
  agent {
    label 'jdk10'
  }
  stages {
    stage('Say Hello') {
      steps {
        echo 'Hello World'
        bat 'java -version'
      }
    }

  }
}
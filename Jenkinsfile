pipeline {
  agent any
  stages {
    stage('Say Hello') {
      steps {
        echo "Hello ${MY_NAME}!"
        bat 'java -version'
      }
    }

  }
  environment {
    MY_NAME = 'Neo'
  }
}
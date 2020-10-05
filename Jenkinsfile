pipeline {
  agent any
  stages {
    stage('Say Hello') {
      steps {
        echo "Hello ${MY_NAME}!"
        echo "${TEST_USER_USR}"
        echo "${TEST_USER_PSW}"
        bat 'java -version'
      }
    }

  }
  environment {
    MY_NAME = 'Neo'
    TEST_USER = credentials('test-user')
  }
}
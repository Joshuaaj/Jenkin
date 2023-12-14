pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        sh 'python3 --version'
      }
    }
    stage('hello') {
      steps {
        sh 'python3 hello.py'
      }
    }  
  }
  post{
    always{
      mail to:"joshuajoz123@gmail.com",
        subject:"joshuajaz36@gmail.com",
        body:"CiCd pipeline"
    }
  }
}

pipeline {
  agent any
  stages {
    stage('Check_Out') {
      steps {
        echo 'Test'
      }
    }
    stage('Build') {
      steps {
        emailext(subject: 'DevOps', to: 'apiizsx@gmail.com', from: 'apiizsx@gmail.com', body: 'TEST')
      }
    }
    stage('') {
      steps {
        echo 'Success'
      }
    }
  }
}
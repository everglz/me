pipeline {
  agent any
  stages {
    stage('Install') {
      steps {
        bat 'C:\\Users\\Cleber\\Desktop\\Jenkins\\install.bat'
      }
    }
    stage('Build') {
      steps {
        bat 'C:\\Users\\Cleber\\Desktop\\Jenkins\\build.bat'
      }
    }
    stage('Test') {
      steps {
        bat 'C:\\Users\\Cleber\\Desktop\\Jenkins\\test.bat'
      }
    }
  }
}
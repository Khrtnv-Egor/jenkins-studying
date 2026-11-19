// Jenkinsfile
// Мой первый пайплайн

pipeline {
  agent none
  stages {
    stage('Check Agent') {
      agent any
      steps {
        echo 'Running on agent...'
        sh 'hostname'
        sh '$WORKSPACE'
	sh '$NODE_NAME'
      }
    }
    stage('Build Info') {
      agent any
      steps {
        echo 'Build information...'
	sh '$BUILD_NUMBER'
	sh '$BUILD_ID'
	sh '$BUILD_URL'
      }
    }
  }
} 

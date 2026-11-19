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
        echo '$WORKSPACE'
	echo '$NODE_NAME'
      }
    }
    stage('Build Info') {
      agent any
      steps {
        echo 'Build information...'
	echo '$BUILD_NUMBER'
	echo '$BUILD_ID'
	echo '$BUILD_URL'
      }
    }
  }
} 

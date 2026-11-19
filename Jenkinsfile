// Jenkinsfile
// Мой первый пайплайн

pipeline {
  agent any
  stages {
    stage('PCheck Agent') {
      steps {
        echo 'Running on agent...'
        sh 'hostname'
        echo '${WORKSPACE}'
	echo '${NODE_NAME}'
      }
    }
  }
} 

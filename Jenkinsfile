pipeline {
  agent { label 'Node' }
  stages {
    stage('checkout') 
      steps {
            checkout scm
		}
    }
    stage('creation of the folder') 
        {
      steps {
        sh 'cd /home/ubuntu ; sudo mkdir rajkumar01'
      }
    }
  }

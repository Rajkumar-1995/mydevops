pipeline { 
	agent any {
    label 'Node' 
    }
    stages {
	stage('Creation of the folder') {
            steps { 
                sh 'cd /home/ubuntu; sudo mkdir kumar1' 
            }
        }
        stage('Creation of the folder on different server'){
            steps {
			     node ( 'my slave' )
				 
                sh 'cd /home/ubuntu; sudo mkdir kumar2'
     
            }
        }
        
    }
}

pipeline { 
    agent any 
    label 'Node' {
        skipStagesAfterUnstable()
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
				 
                sh 'sh cd /home/ubuntu; sudo mkdir kumar2'
     
            }
        }
        
    }
}

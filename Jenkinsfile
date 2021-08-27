pipeline {
 agent {
 label 'Node'
}
stages {
 stage ( 'checkout' )
{
 steps 
    {
	   checkout scm
    }
}
 stage ( 'creation of the folder' )
     {
	steps
	{
		sh "cd /home/ubuntu ; sudo mkdir testfolder "
	}
}
 stage ( 'creating the folder on different server ' )
    {
	steps {
		node ( 'my slave' ) {
	
	    sh "cd/var/www; sudo mkdir jenkins1
		}
	}
}
}

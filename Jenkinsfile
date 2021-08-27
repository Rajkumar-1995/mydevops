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
	 stage ( 'creationf of folder' )
	 {
		 steps
		 {
			 sh "cd/home/ubuntu ; sudo mkdir raj12"
		 }
	 }
	 stage ( 'creating folder on different server' )
	 {
		 steps {
			 node ( 'my slave' ) {
				 sh "cd/var/www ; sudo mkdir raj123"
			 }
		 }
	 }
	}

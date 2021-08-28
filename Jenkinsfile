pipeline {
	"agent any" {
	label 'Node'
}
stages
     stage ('checkout')
 {
	 steps 
	 {
              checkout SCM
	 }
 }
     stage  ('creation of the folder')
         {
	 steps
	 {
		 
	    sh "cd /home/ubuntu ; sudo mkdir raj12"
		 
	 }
     }
}

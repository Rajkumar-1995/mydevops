pipeline {
	agent any 
	label 'Node'
}
stages
  stage ('cehckout')
 {
	 steps 
	 {
		checkout sm
	 }
 }
  stage  ('creation of the folder')
    {
	    steps {
	    sh "cd /home/ubuntu ; sudo mkdir raj12"
	}
   }
}

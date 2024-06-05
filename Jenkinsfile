node{
	

		stage('checkout'){
			
				checkout scm
			
			
		}
		
		stage('compile'){
			
				sh 'javac Scripted.java'
			
		}

		stage('execute'){
			
				sh 'java Scripted'
				
		}

		stage('display'){
		
			  sh	'cat file.txt'
			
			
		}
		


	
	

}

node{
	stages{
		stage('checkout'){
			steps{
				checkout scm
			}
			
		}
		
		stage('compile'){
			steps{
				sh 'javac Scripted.java'
			}
		}

		stage('execute'){
			steps{
				sh 'java Scripted'
			}	
		}

		stage('display'){
			steps{
			  sh	'cat file.txt'
			}
			
		}
		


	
	}

}

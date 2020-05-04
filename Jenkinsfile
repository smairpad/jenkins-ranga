pipeline {
	agent any 
	stages {
		stage ("Build") {
			steps {
				echo "Build"
			}
		}
		stage ("Test") {
			steps {
				echo "Test"
			}
		}
	 stage ("Integration Test") {
			steps {
				echo "Integration Test"
			}
		}
	}
	post {
		always {
			echo "Iam Awesome always"
		}
		success {
			echo "Irun when u r succesfull"
		}
		failure {
			echo "I run when u fail"
		}
	
	
	}
		
		
}

pipeline {
	//agent any 
	agent {docker {image 'maven:3.6.3'} }
	stages {
		stage ("Build") {
			steps {
				sh 'mvn --version'
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

// Scripted
//Declarative
pipeline {

	//agent any
	agent { docker {image 'maven:3.6.3'}}
	stages{
		stage('build'){
			steps {
				sh "mvn --version"
				echo "Build"
			}
		}

		stage('Test'){
			steps {
				echo "Test"
			}
		}

		stage('Integration Test'){
			steps {
				echo "Integration Test"
			}
		}

	} 
	post {
		always {
			echo 'Im Awesome, I run always'
		}
		success {
			echo 'I run when you are successul'
		}
		failure {
			echo 'when you fail, I fail'
		}
	}
}

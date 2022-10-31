// Scripted
//Declarative
pipeline {

	agent any
	stages{
		stage('build'){
			steps {
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
		fail {
			echo 'when you fail, I fail'
		}
	}
}

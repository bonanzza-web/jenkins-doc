pipeline {
	agent { docker { image 'python:latest' }}
	stages {
		stage ('first') {
			steps {
				echo "Zalupa"
				sh "python --version"
			}
		}
	}
}

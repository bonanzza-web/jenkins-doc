pipeline {
	agent { docker { image 'httpd:latest' }}
	stages {
		stage ('first') {
			steps {
				echo "Zalupa"
				sh "ls -la"
			}
		}
	}
}

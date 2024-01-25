pipeline {
	agent { docker { image 'httpd' }}
	stages {
		stage ('first') {
			steps {
				echo "Zalupa"
				sh "ls -la"
			}
		}
	}
}

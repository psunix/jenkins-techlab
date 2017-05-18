pipeline {
	agent any
	stages {
		stage('Build') {
			steps {
				script {
					def company = 'acme'
					echo 'join the ${company}'
					echo "join the ${company}"
					echo '''join the ${company}'''
					echo """join the ${company}"""
				}
			}
		}
	}
}

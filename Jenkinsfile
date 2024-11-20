pipeline {
	agent { docker { image 'python:3.13.0-alpine3.20' }}
	stages {
		stage("Build") {
			steps {
				sh 'python -V'
			}
		}
	}
}
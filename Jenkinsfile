pipeline {
	agent any
	stages {
		stage("Building Project"){
			steps {
				sh "mvn -Dmaven.test.failure.ignore=true clean install"
			}
		}
	}
}
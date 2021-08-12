pipeline {
	agent any
	stages {
		stage('build') {
			steps {
				echo 'building'
				make clean
				make all
			}
		}
	}
}

pipeline {
	agent any
	stages {
		stage ('Checkout') {
			steps {
				checkout master
			}
		}

		stage('build') {
			steps {
				echo 'building'
				make clean
				make
			}
		}
	}
}

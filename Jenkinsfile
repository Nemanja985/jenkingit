pipeline {
    agent any
    stages {
	stage('Build') {
            steps {
                echo 'Building..'
            }
        }
	stage('Testing') {
            steps {
                sh "php test"
            }
        }
    }
}

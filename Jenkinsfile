pipeline {
    agent any
    stages {
	stage('Build') {
            steps {
                echo 'Building..'
            }
        }
	stage('Deploy') {
            steps {
                php jenkinsgit.php
            }
        }
    }
}

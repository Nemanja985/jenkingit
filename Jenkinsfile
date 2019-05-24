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
                sh "php jenkinsgit.php"
            }
        }
    }
}

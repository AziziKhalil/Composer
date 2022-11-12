pipeline {
agent any

stages {

			stage('Docker compose') {
            steps {
            sh 'docker-compose up -d';
			}  
			}
			
			stage('Wait 120s') {
            steps {
			sh 'sleep 120'
			}  
			}
}
}
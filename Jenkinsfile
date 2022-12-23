pipeline {
    agent none
    stages {
        stage('build') {
            steps {
                echo "Hello World!"
            }
        }
	stage('Email Notification'){
	mail bcc: '', body: 'Success', cc: '', from: '', replyTo: '', subject: 'Jenkins Build', to: 'satheshdevel@gmail.com'
    }
}

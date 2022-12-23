pipeline {
    agent any
     
    stages {
        stage('Ok') {
            steps {
                echo "Success"
            }
        }
    }
    post {
        always {
            mail bcc: '', body: 'Jenkins Build for web laravel', cc: '', from: '', replyTo: '', subject: 'Test Jenkins', to: 'alexander@rattletech.in'
        }
    }
}

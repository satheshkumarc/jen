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
            mail bcc: '', body: 'Jenkins Build', cc: '', from: '', replyTo: '', subject: 'Test Jenkins', to: 'satheshdevel@gmail.com'
        }
    }
}

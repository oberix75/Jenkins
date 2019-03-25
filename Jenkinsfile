pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'netstat -lapute'
                sh '''
                    ss -lataup
                    lsof -l
                '''
            }
        }
    }
}

pipeline {
    agent { dockerfile true }
    stages {
        stage('Launch') {
            steps {
                sh 'python /root/jenkins/apptest.py'
            }
        }
        stage('Echo') {
            steps {
                sh 'whoami'
            }
        }
    }
}

pipeline {
    agent { dockerfile true }
    stages {
        stage('Launch') {
            steps {
                sh 'python /root/jenkins/app/test.py'
            }
        }
        stage('Echo') {
            steps {
                sh 'whoami'
            }
        }
    }
}

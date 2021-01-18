pipeline {
    agent { dockerfile true }
    stages {
        stage('Print'){
            step{
                python "/root/jenkins/test.py"
            }
        }

        stage('Echo') {
            steps {
                sh 'whoami'
            }
        }
    }
}

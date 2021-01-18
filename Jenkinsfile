pipeline {
    agent { dockerfile true }
    stages {
        stage('Print'){
            steps{
                python '/root/jenkins/test.py'
            }
        }

        stage('Echo') {
            steps {
                sh 'whoami'
            }
        }
    }
}

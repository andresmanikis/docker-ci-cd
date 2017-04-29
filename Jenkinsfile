pipeline {
    agent { docker 'node:6.3' }
    stages {
        stage('Test') {
            steps {
                sh npm install
                sh npm test
            }
        }
    }
}
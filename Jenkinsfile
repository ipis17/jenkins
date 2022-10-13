pipeline {
    agent {
        docker { image 'node:16.17.1-alpine3.15' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
}

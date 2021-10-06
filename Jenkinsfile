pipeline {
    agent any
    stages {
        stage('Build'){
            steps{
                echo "Build"
            }
        }
        stage('Test'){
            steps{
                echo "Test"
            }
        }
        stage('Integration Test'){
            steps{
                echo "Integration Test"
            }
        }
    } 
    post{
        always{
            echo "I run always"
        }
        success{
            echo "I run sucess"
        }
        failure{
            echo "I run failure"
        }
    }
}

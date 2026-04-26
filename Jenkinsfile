pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                git 'https://github.com/Rachana5856/cloud-devops-project.git'
            }
        }

        stage('Verify Files') {
            steps {
                sh 'pwd'
                sh 'ls -la'
            }
        }

        stage('Terraform Version') {
            steps {
                sh 'terraform version || echo Terraform not installed yet'
            }
        }

        stage('Success') {
            steps {
                echo 'Cloud DevOps Pipeline Build Successful!'
            }
        }
    }
}
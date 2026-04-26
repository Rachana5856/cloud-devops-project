pipeline {
    agent any

    stages {
        stage('GitHub Checkout') {
            steps {
                git 'https://github.com/Rachana5856/cloud-devops-project.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Build successful!'
            }
        }
    }
}
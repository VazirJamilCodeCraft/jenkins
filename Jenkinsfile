pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git url: 'https://github.com/VazirJamilCodeCraft/jenkins.git', branch: 'main'
            }
        }

        stage('Build') {
            steps {
                echo 'Build stage...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
    }
}

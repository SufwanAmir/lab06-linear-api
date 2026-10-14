pipeline {
    agent any

    triggers {
        githubPush()
    }

    stages {
        stage('Deploy Linear Regression API') {
            steps {
                sh 'docker compose up -d'
            }
        }
    }
}

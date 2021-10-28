pipeline {
    agent any

    stages {
        stage('Main branch') {
            when {
                branch "main"
            }
            steps {
                echo "main branch"
            }
        }
        stage('dev branch') {
            when {
                branch "dev"
            }
            steps {
                echo "dev branch"
            }
        }
        stage('Prod branch') {
            when {
                branch "prod"
            }
            steps {
                echo "prod branch"
            }
        }
        
    }
}

pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Building project..."
            }
        }

        stage('Deploy') {
            when {
                branch 'feature'  
            }
            steps {
                echo "Deploying to Production (feature branch only)"
            }
        }
    }
}

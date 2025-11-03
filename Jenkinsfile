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
                branch 'main'  
            }
            steps {
                echo "Deploying to Production (main branch only)"
            }
        }
    }
}

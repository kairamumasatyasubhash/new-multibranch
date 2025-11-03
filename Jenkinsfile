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
                branch 'master'  
            }
            steps {
                echo "Deploying to Production (master branch only)"
            }
        }
    }
}

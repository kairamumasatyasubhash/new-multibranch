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
                branch 'subhash'  
            }
            steps {
                echo "Deploying to Production (subhash branch only)"
            }
        }
    }
}

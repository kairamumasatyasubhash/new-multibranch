pipeline {
    agent any
    stages {
        stage('Create and Switch Directory') {
            steps {
                sh '''
                    mkdir myfolder         
                    cd myfolder             
                    echo "Now inside myfolder" > test.txt
                    ls                      
                '''
            }
        }
    }
}

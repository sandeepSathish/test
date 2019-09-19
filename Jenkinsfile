pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                script {
                    
                   sh 'dir=\$(cat /root/file1)'
                    sh 'echo "Service user is $dir"'
                
                  
                   
                }
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}

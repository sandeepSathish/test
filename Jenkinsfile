pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                script {
                    
                   sh 'dir=\$(cat /root/file1)'
                    sh echo "${dir}"
                  
                    sh 'mkdir /home/ec2-user/build/"${dir}"'
                    sh 'cd /home/ec2-user/build/"${dir}"'
                   sh 'pwd'
                  
                   
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

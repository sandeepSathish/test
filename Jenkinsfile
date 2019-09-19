pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                script {
                    
                  dir=`date | awk -F ' ' '{print $(NF-2)}'`
                   sh 'mkdir /home/ec2-user/build/$dir'
                  sh 'cd /home/ec2-user/build/$dir'
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

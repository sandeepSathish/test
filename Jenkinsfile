pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                script {
                    sh """
                   dir=`date | awk -F ' ' '{print $(NF-2)}'`
                   mkdir /home/ec2-user/build/$dir
                   cd /home/ec2-user/build/$dir
                   pwd
                   """
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

pipeline {
    agent any

    stages {
      
         stage('Checkout code') {
        steps {
            checkout scm
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

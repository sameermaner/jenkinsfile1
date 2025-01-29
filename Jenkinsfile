
pipeline {
    agent any
    stages { 
        stage('Install Dependencies') {
            steps {
                sh 'npm install express'
            }
        }
 
 
        stage('Run Tests') {
            steps {
                sh 'npm test'
            }
        }
    }
 }


pipeline {
    agent any
    stages { 
        stage('Install Dependencies') {
            steps {
                sh 'npm install express'
            }
        }
 
        stage('Build App') {
            steps {
                sh 'npm run build'
            }
        }
 
        stage('Run Tests') {
            steps {
                sh 'npm test'
            }
        }
    }
 }

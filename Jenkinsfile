
pipeline {
    agent any
 
        stage('Install Dependencies') {
            steps {
                sh 'npm install'
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

pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'building'
            }
        }
    stage('Test') {
            steps {
                sh 'testing'
            }
        }
    stage('Deploy') {
            steps {
                sh 'deploying'  
            }    
        }
    }
}
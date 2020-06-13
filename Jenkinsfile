pipeline {
    agent {
        docker {
            image 'node:6-alpine' 
            args '-d -p 3000:3000' 
        }}
    environment {
        HOME = '.'
    }
    
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}

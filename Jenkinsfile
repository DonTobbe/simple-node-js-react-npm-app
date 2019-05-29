pipeline {
    agent any 

    tools {nodejs "node"}

    stages {
        stage('Build') { 
            steps {
                bat 'npm install' 
            }
        }
        stage('Build production files') { 
            steps {
                bat 'npm run build' 
            }
        }
        stage('Test vad som händer') { 
            steps {
                bat 'npm run test' 
            }
        }
        
        stage ('Run'){
            steps {
                echo 'Testa att packa ner och installera'
            }
        }
    }
}
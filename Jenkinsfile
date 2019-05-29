pipeline {
    agent any 

    tools {nodejs "node"}

    stages {
        stage('Build') { 
            steps {
                bat 'npm install' 
            }
        }
        stage('Build productions files') { 
            steps {
                bat 'npm run build' 
            }
        }
        stage ('Run'){
            steps {
                echo 'Testa att packa ner och installera'
            }
        }
    }
}
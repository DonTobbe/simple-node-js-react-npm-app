pipeline {
    agent any 

    tools {nodejs "node"}

    stages {
        stage('Build') { 
            steps {
                bat 'npm install' 
            }
        }
        stage ('Run'){
            steps {
                echo 'Testa att packa ner och installera'
            }
        }
    }
}
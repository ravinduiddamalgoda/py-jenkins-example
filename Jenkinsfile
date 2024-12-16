pipeline {
    agent any

    stages {
        stage('Setup') {
            steps {
                sh "pip install -r requirements.txt"
            
            }
        }
        stage('Test') {
            steps {
                sh "pytest"
                
            }
        }    
        stage('Deployment') {
            steps {
                echo "Running Deployment"
                
            }
        } 
        
            
    }
}


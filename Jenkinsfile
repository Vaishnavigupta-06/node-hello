pipeline {
    agent any
   
    stages {
        
        stage('Build') {
            steps {
                
                sh 'npm pack'
                sh 'npm start'
                
            }
        }
        stage('Start') {
            steps {
                
               
                sh 'npm start'
                
            }
        }
        stage('Deploy') {
            steps {
                sh ' echo "deploying" '
                
            }
        }
     }
  
}

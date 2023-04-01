pipeline {
    agent any
   
    stages {
        
        stage('Build') {
            steps {
                
                sh 'npm pack'
                
            }
        }
        stage('Testing') {
            steps {
                sh 'npm install karma'
                sh 'karma run'
                
            }
        }
     }
  
}

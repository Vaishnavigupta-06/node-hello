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
                sh 'karma run'
                
            }
        }
     }
  
}

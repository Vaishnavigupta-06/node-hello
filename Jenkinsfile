pipeline {
    agent any
   
    stages {
        
        stage('Build') {
            steps {
                
                sh 'npm pack'
                
            }
        }
        stage('Deploy') {
            steps {
                sh 'npm start'
                
            }
        }
     }
  
}

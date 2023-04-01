pipeline {
    agent any
   
    stages {
        
        stage('Build') {
            steps {
                
                sh 'npm pack'
                sh 'npm start'
                
            }
        }
        stage('Test') {
            steps {
                sh 'echo " testing" '                
            }
        }
     }
  
}

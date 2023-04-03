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
    post{
        success{
            mail to: "aayush.bisht@knoldus.com",
            subject: "Build is successfull",
  body: "success"    
        }     
    failure{
mail to: "vaishnavi.g@knoldus.com",
  subody: "failed"
 }
  }
  
}

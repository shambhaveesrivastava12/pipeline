pipeline{
    
    agent any 
    
    stages {
        
        stage('Git Checkout'){
            
            steps{
                
                
                    
                    git branch: 'main', url: 'https://github.com/shambhaveesrivastava12/pipeline.git'
                
            }
        }
        stage('UNIT testing'){
            
            steps{
                
                script{
                    
                    sh 'mvn test'
                }
            }
        }
    }
}
pipeline{
    
    agent any 
    
    stages {
        
        stage('Git Checkout'){
            
            steps{
                
                script{
                    
                    git branch: 'main', url: 'https://github.com/shambhaveesrivastava12/pipeline.git'
                }
            }
        }
    }
}
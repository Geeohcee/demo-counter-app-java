pipeline{
    
    agent any 
    
    stages {
        
        stage('Git Checkout'){
            
            steps{
                
                script{

                    git 'https://github.com/Geeohcee/demo-counter-app-java.git'
                    // git branch: 'main', url: 'https://github.com/Geeohcee/demo-counter-app-java.git'
                }
            }
        }
pipeline {
    agent any 
    
    stages {
        stage('Git Checkout') {
            steps {
                script {
                    git branch: 'master', url: 'https://github.com/Geeohcee/demo-counter-app-java.git'
                }
            }
        } // <-- Added the closing curly brace for the 'Git Checkout' stage
        
        stage('UNIT testing') {
            steps {
                script {
                    sh 'mvn test'
                }
            }
        }
    }
}

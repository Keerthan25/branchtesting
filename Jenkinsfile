pipeline{
    agent any
    stages{
         stage('branch name'){
            steps{
                echo 'this is feature branch'
            }
         }      
       stage('Git Checkout Stage'){
            steps{
                git branch: 'main', url: 'https://github.com/artisantek/sonarqube-example.git'
            }
         }        
       stage('Build Stage'){
            steps{
                sh 'mvn clean install'
            }
         }
    
                }
            }
    

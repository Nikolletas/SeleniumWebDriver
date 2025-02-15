pipeline{
    agent any
    stages{
        stage('App Restore'){
            steps{
                bat 'dotnet restore'
            }  
        }
        stage('App Install'){
            steps{
                bat 'dotnet build'
            }  
        }
        stage('Run tests'){
            steps{
                bat 'dotnet test'
            }
        }
    }
}
pipeline {
    agent any

    stages {
        stage('Build project') {
            steps {
                bat 'dotnet restore'
                bat 'dotnet build'
            }
        }
        stage('Run tests') {
            steps {
                bat 'dotnet test'
            }
        }
    }
}
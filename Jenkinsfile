pipeline {
    // trigger comment 
    agent any
        stages {
            stage('Build App') {
                steps {
                   bat 'npm install'
                }
            }
            //trigger testing
            stage('Run Tests') {
                steps {
                    bat 'dotnet test'
                }
            }
        }
}

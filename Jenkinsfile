pipeline {
    // trigger comment 
    agent any
        stages {
            stage('Build App') {
                steps {
                   bat 'dotnet build'
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

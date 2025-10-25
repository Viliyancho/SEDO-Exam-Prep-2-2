pipeline{
    agent any
    //change 1
    stages{
        stage("Build the application"){
            steps{
                bat 'dotnet build'
            }
        }
        stage("Run the tests"){
            steps{
                bat 'dotnet test --no-build --verbosity normal'
            }
        }
    }
}
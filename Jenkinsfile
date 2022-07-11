pipeline{
    agent any
    stages{
        stage("Build"){
            steps{
                echo "Hello World"
                sh '''

                    dotnet run ${WORkSPACE}/HelloWorld.csproj

                   '''
            }
        }
    }
}
pipeline{
    agent any
    stages{
        stage("Build"){
            steps{
                echo "Hello World"
                sh '''#!/bin/bash

                    dotnet run ${WORkSPACE}/HelloWorld.csproj

                   '''
            }
        }
    }
}
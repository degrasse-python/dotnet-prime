pipeline {
  agent none
  stages {
    stage('Nuget Restore') {
      agent any
      steps {
        bat(label: 'Nuget Restore', script: 'nuget restore "PrimeDotnet\\prime-dotnet.sln"')
        bat 'echo "Nuget Done Starting Msbuild *************"'
      }
    }

        bat 'nuget restore "PrimeDotnet\\prime-dotnet.sln"'
        bat 'echo "Nuget Done Starting Msbuild *************"'
         
            }
          }
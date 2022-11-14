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

<<<<<<< HEAD
        bat 'nuget restore "PrimeDotnet\\prime-dotnet.sln"'
        bat 'echo "Nuget Done Starting Msbuild *************"'
         
            }
          }
=======
>>>>>>> fb818da7f2317a4ef663d92a1b9e0392327231f6
  }
}
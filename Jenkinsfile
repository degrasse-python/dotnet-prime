pipeline {
  agent none
  stages {
    stage('Nuget Restore') {
      agent any
      steps {
        bat 'nuget restore "PrimeDotnet\\prime-dotnet.sln"'
        bat 'echo "Nuget Done Starting Msbuild *************"'
      }
    }
  }
}
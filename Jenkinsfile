pipeline {
  agent none
  stages {
    stage('Nuget Restore'){
      agent any
      //when { anyOf { branch releaseBranch; branch mainBranch } }

      /*  'Deploy' agent pod template
      agent {
          kubernetes {
              cloud kubernetes
              label 'windows'
              yaml windowsAgentYaml
          }
      }
      */
      steps {

        bat label: 'Nuget Restore', 
        script: '''
          nuget restore "PrimeDotnet\\prime-dotnet.sln"
          echo "Nuget Done Starting Msbuild *************"
        ''' 
            }
          }
  }
}
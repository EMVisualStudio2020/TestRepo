pipeline {
  agent any

  stages {
    stage("build") {
      steps {
        echo "Building the application..."
        bat "\"${tool 'MSBuild'}\" DockerrApi.sln /p:Configuration=Debug /p:Platform=\"Any CPU\""
      }
    }
      stage("test") {
        steps{
        echo "Testing the application..."
      }
      }
      
      stage("deploy")
      {
        steps {
        echo "Deploying the application.."
        }
      }
    }}

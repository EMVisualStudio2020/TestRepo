pipeline {
  agent any

  stages {
    stage("build") {
      steps {
        echo "Building the application..."
        bat "msbuild.exe DockerrApi.sln"
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

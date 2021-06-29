pipeline {
  agent any
  
  stages {
    stage("build") {
      steps {
        echo "Building the application..."
        sh 'dotnet build'
      }
    }
  }
}

pipeline {
  agent any
  stages {
    stage {
      steps {
        echo 'Run build automation'
        sh './gradlew build --no-daemon'
        archiveArtifact artifact: 'dist/trainSchedule.zip'
        
      }
    }
  }
}

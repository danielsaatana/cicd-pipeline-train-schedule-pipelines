pipeline {
  agent any
  stages {
    stage ('build') {
      steps {
        echo 'Run build automation'
        sh './gradlew build --no-daemon'
        archiveArtifact artifact: 'dist/trainSchedule.zip'
        
      }
    }
  }
}

pipeline {
  agent any
  
  stages {
    stage("Build") {
      steps {
        sh "./gradlew build"
      }
    }
    stage("Archive") {
      steps {
        archiveArtifacts 'dist/trainSchedule.zip'
      }
    }
  }
}

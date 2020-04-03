pipeline {
  stages {
    stage("Build") {
      step {
        sh "./gradlew build"
      }
    }
    stage("Archive") {
      step {
        archiveArtifacts 'dist/trainSchedule.zip'
      }
    }
  }
}

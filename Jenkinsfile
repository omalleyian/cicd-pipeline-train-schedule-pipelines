pipeline {
  stages {
    stage("Build") {
      sh "./gradlew build"
    }
    stage("Archive") {
      archiveArtifacts 'dist/trainSchedule.zip'
    }
  }
}

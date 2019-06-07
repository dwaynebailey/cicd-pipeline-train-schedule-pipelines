pipeline [
  stage "Build" {
    sh "./gradlew build --no-daemon"
    archiveArtifact {
      pattern("dist/trainSchedule.zip")
      onlyIfSuccessfull()
    }
  }
]

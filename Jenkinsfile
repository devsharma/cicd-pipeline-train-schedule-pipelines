pipeline {
  agent any
  stages ('Build') {
    steps {
      echo 'Running Build AUtomation'
      sh './gradlew build --no-daemon'
      archiveArtifacts aritfacts: 'dist/treainSchedule.zip'
    }
  }
}

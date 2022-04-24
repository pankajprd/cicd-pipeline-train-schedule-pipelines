pipeline {
  agent any
  stages {
    stage ('build') {
      echo 'building automation'
      sh './gradlew build --no-deamon'
      archiveArtifacts artifacts: '/dist/trainSchedule.zip' 
    }
  }
}

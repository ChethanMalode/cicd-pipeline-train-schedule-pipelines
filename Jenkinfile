pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        echo "Running smoothly"
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
        }
      }
    }
 } 

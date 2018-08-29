pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        echo 'Running Build automation'
        sh './gradelw build --no-demon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
        }
       }
      }
     }

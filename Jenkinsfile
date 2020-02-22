pipeline{
  agent any
  stages{
    stage ('build'){
      steps{
        echo'building'
        sh './gradlew build --no-deamon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    
    }
  }
}

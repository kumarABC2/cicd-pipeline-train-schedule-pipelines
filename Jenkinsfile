pipeline{
   agent any
   stages {
     stage ('Buils') {
       steps {
         echo 'Running build automation'
         sh './gradlew build --no-daemon'
         archiveArtifacts artifacts: 'dist/trainSchedule.zip'
     }
    }
  }
}

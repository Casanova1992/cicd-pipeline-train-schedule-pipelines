pipeline {
  agent any 
  stages ('Build')
    {
      steps {
         echo "Running build automation "
         sh './gradlew build --no-daemon'
         archieveArtifacts artifacts:'dist/trainSchedule.zip
      }
      }
}

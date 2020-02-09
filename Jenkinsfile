pipeline {
   agent any 
   stages ('build') 
   {
      steps
      {
         echo 'Runing build automation'
         sh './gradlew.build --no-deamon'
         archiveArtifacts artifacts: 'dist/trainSchedule.zip'
       }   
   
   }
}

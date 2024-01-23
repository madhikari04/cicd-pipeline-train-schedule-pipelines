pipeline {
 agent any 
 stages {
   stage ('build'){
     steps {
       echo "Running build automation' 
       sh './gradlew build --no-daemon'
       archieveArtifacts artifacts: 'dis/trainSchedule.zip'
     }
   }
 }
}
 

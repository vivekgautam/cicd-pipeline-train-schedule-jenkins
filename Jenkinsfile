pipeline{
      agent any
        stages{
          stage('Build'){
            echo 'Running Build Automation'
            sh './gradlew build --no-daemon'
            archiveArtifacts artifact: 'dist/trainSchedule.zip'
          
          }
      
      }



}

Pipeline{
  agent any
  stages{
    stage ('Build'){
      steps {
        echo 'Runing build automation'
        sh './gradle build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainschedule.zip'
      }
    }
  }
}

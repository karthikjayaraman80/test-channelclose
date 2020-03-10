pipeline {
  agent {
    label 'debug-channelclose'
  }  
  stages {
    stage ('Debug Issue') {
      steps {
        sh 'cat debug-channelclose.txt'
        //archiveArtifacts 'build_output.log'
      }
    }
  }
}

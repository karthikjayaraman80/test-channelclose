pipeline {
  agent {
    label 'test-channelclose'
  }  
  stages {
    stage ('Debug Issue') {
      steps {
        sh 'cat debug_channelclose.txt'
        //archiveArtifacts 'build_output.log'
      }
    }
  }
}

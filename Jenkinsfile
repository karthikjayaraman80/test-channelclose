pipeline {
  agent {
    label 'test-channelclose'
  }  
  stages {
    stage ('Debug Issue') {
      steps {
        sh 'cat build_output.log'
        //archiveArtifacts 'build_output.log'
      }
    }
  }
}

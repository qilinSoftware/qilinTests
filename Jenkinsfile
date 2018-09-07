node {  
  stage ('Init') {
    checkout scm
    bat '''
        F:/qilin-dev/5_Executable/QilinRemote/QilinRemote.cmd %QILIN_SERVER% %BRANCH_NAME% testQilin.sah null ie
        
    '''
    archiveArtifacts "%BRANCHE_NAME%.html"
  }
}

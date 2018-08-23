node {  
  stage ('Init') {
    checkout scm
    bat '''
        F:/qilin-dev/5_Executable/QilinRemote/QilinRemote.cmd %QILIN_SERVER% %JOB_BASENAME% testQilin.sah null ie
        
    '''
  }
}

node {  
  stage ('Init') {
    scm checkout
    bat '''
        F:/qilin-dev/5_Executable/QilinRemote/QilinRemote.cmd %QILIN_SERVER% %JOB_BASENAME% testQilin.sah null ie
        
    '''
  }
}

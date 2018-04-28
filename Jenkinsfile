node {
   scm checkout 
   sh '''
        ls -lhrt
    '''
   def rootDir = pwd()
   println("Current Directory: " + rootDir)

    // point to exact source file
    def example = load "${rootDir}/c"

   // example.exampleMethod()
    // example.otherExampleMethod()
}
   

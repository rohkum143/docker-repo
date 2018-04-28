node {
   scm checkout 
   sh '''
        ls -lhrt
    '''
   def rootDir = pwd()
   println("Current Directory: " + rootDir)

    // point to exact source file
    def example = load "${rootDir}/Example.Groovy"

   // example.exampleMethod()
    // example.otherExampleMethod()
}
   

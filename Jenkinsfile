node {
    // Git checkout before load source the file
   // checkout scm

	sh "git clone https://github.com/rohkum143/docker-repo.git"
	sh " git rev-parse test > commandresult"
	
	def proc = readFile('commandresult').trim()
	println proc
		//def proc = "git rev-parse test"
    // To know files are checked out or not
    /* sh '''
        ls -lhrt
    ''' */
	if ( proc.contains != 'null') {
		
			echo "Found test tag"
	        currentBuild.result = 'FAILED'		 
	}	 
	else {
              echo "create tag for test"
		 }
   /* git push origin ${mvn_version}
         fi "
    def rootDir = pwd()
    println("Current Directory: " + rootDir)
    // point to exact source file
    def example = load "${rootDir}/Example.Groovy"
     example.test("tom")
    // example.otherExampleMethod()
    def shortCommit = sh(returnStdout: true, script: "git log -n 1 --pretty=format:'%h'").trim()
    println (shortCommit) */
}

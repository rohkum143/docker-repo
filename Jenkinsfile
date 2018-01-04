node('docker') {
    stage('checkhostname') {
	    parallel (
	             "task1": { sh 'touch /tmp/docker-${BUILD_NUMBER}' },
	              "task2": { sh 'touch /tmp/docker1-${BUILD_NUMBER}' },
		     )
	                    	
                   }
                }

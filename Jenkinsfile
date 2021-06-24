@Library('shared-library-new') _

pipeline {
  agent any 
		tools {
		jdk 'JAVA'
		git 'Default'
	}
    stages {
	
stage('Git Checkout') {
    codecheckout(
        branch: "main",
        url: "https://github.com/iambasil13/cts-apprepo.git"
    )
}
		}
		
	}

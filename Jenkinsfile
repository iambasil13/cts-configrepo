@Library('shared-library-new') _
 
pipeline {
    agent any
    stages {
        stage('Git Checkout') {
            steps {
            codecheckout(
                branch: "main",
                url: "https://github.com/iambasil13/cts-apprepo.git"
            )
            }
    }
    }
}

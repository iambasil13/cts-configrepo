@Library('shared-library-new') _
 
pipeline {
    agent any
    stages {
        stage('Git Checkout') {
            steps {
            stepcodecheckout(
                branch: "main",
                url: "https://github.com/iambasil13/cts-apprepo.git"
            )
            }
    }
    }
}

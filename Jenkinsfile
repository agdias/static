pipeline {
    agent any {
        stages {
            stage('Upload to AWS') {
                steps {
                    withAWS(region: 'us-west-2a',credentials: 'aws-static') {
                        
                    }
                }

            }
        }
    }
}
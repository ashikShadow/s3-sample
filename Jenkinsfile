pipeline {
    agent any
    stages {
      stage("Pushing file to s3") {
            steps {
                sh """     
                     aws s3 cp /var/lib/jenkins/workspace/s3-file-transfer s3://flawless-auto-deployment --recursive
                """
            } 
        } 
      
    }
}

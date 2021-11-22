pipeline {
    agent any
    stages {
      stage("Pushing file to s3") {
            steps {
                sh """     
                     pwd 
                     aws s3 cp ./ --recursive s3://flawless-auto-deployment
                """
            } 
        } 
      
    }
}

pipeline {
    agent any
    stages {
      stage("Pushing file to s3") {
            steps {
                sh """        
                    aws s3 ls
                    aws s3 rm s3://flawless-auto-deployment --recursive
                    aws s3 cp ./ --recursive s3://flawless-auto-deployment
                """
            } 
        } 
      
    }
}

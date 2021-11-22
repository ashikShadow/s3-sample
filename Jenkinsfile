pipeline {
    agent any
    stages {
      stage("Pushing file to s3") {
            steps {
                sh """        
                    aws s3 ls
                """
            } 
        } 
      
    }
}

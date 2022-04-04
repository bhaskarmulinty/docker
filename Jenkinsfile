pipeline {
    agent any

    stages {
         
        stage ("Voting App Image Build") {
            steps {
                sh ("cd /var/lib/jenkins/workspace/docker/vote/ ")
                sh ("docker build . -t voting-app ") 
            }
        }
        
        
    }
}

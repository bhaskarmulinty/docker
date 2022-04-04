pipeline {
    agent any

    stages {
         
        stage ("Voting App Image Build") {
            steps {
                sh ("docker build /var/lib/jenkins/workspace/vote -t voting-app ") 
            }
        }
        
        
    }
}

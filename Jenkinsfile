pipeline {
    agent any

    stages {
         
        stage ("Voting App Image Build") {
            steps {
                sh ("docker build $jenkins_vote -t voting-app ") 
            }
        }
        
        
    }
}

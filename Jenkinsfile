pipeline {
    agent any

    stages {
         
        stage ("Voting App Image Build") {
            steps {
                sh ("docker build . -t voting-app ") 
            }
        }
        
        stage ("Worker App Image Build") {
            steps {
                sh ('docker build . -t worker-app') 
            }
        }

        stage (" result app Image Build") {
            steps {
                
                sh ('docker build . -t result-app') 
           }
        }
        stage (" images build status") {
            steps {
                echo "Successfully "
                
           }
        }
    }
}

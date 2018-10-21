#!groovy

pipeline { 
    agent any 
    stages {
        stage('Build') { 
            steps { 
                cp /Users/vineetsharma/Documents/catweb/app.py /Users/vineetsharma/DOCKER/catweb/
                cp /Users/vineetsharma/Documents/catweb/index.html /Users/vineetsharma/DOCKER/catweb/templates/
            }
        }
    }
}

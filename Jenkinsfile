#!groovy

pipeline { 
    agent any 
    stages {
        stage('Build') { 
            steps { 
                sh "cp /Users/Shared/Jenkins/Home/workspace/catweb/app.py /Users/vineetsharma/DOCKER/catweb/"
                sh "cp /Users/Shared/Jenkins/Home/workspace/catweb/index.html /Users/vineetsharma/DOCKER/catweb/templates/"
            }
        }
    }
}

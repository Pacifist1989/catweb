#!groovy

pipeline { 
    agent any 
    stages {
        stage('Build') { 
            steps { 
                sh "docker container run -itd -p 5000:5000 -v /Users/vineetsharma/DOCKER/catweb:/usr/src/app/ pacfisit1989/catweb"
                sh "cp /Users/Shared/Jenkins/Home/workspace/catweb/app.py /Users/vineetsharma/DOCKER/catweb/"
                sh "cp /Users/Shared/Jenkins/Home/workspace/catweb/index.html /Users/vineetsharma/DOCKER/catweb/templates/"
            }
        }
    }
}

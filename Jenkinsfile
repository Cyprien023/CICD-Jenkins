pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the application '
            }
        }
    }
    post {
            //Actions post-build
    }
    tools {
        nodejs "NodeJS 20"
    }
}
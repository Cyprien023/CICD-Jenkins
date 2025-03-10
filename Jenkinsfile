pipeline {
    agent any

    tools {
        nodejs "NodeJS 20"
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building the application'
            }
        }
    }

    post {
        always {
            echo 'Pipeline terminé'
        }
    }
}

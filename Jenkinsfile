pipeline {
    agent any

    stages {

        stage('Clone Repository') {
            steps {
                echo "Cloning GitHub Repository..."
                git branch: 'main', url: 'https://github.com/amarnathlog4688/static-web-hostingp.git'
            }
        }

        stage('Build') {
            steps {
                echo 'No build needed for static website'
            }
        }

        stage('Test') {
            steps {
                echo 'No tests for static website'
            }
        }
    }
}

pipeline {
    agent any

    stages {

        stage('Clone Repository') {
            steps {
                git branch: 'main', url: 'https://github.com/nikhil-stackly/pos-demo.git'
            }
        }

        stage('Build') {
            steps {
                echo "Building the POS project..."
            }
        }

        stage('Test') {
            steps {
                echo "Running POS tests..."
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying POS application..."
            }
        }

    }
}

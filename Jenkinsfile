pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                echo "Cloning repo..."
                checkout scm
            }
        }
        stage('Build') {
            steps {
                echo "Building project..."
            }
        }
        stage('Test') {
            steps {
                echo "Running tests...."
            }
        }
        //aaaa

        stage('Deploy') {
            steps {
                echo "Deploying..."
            }
        }
    }
}

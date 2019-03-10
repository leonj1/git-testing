#!groovy

pipeline {
    agent any 
    stages {
        stage('Checkout') { 
            steps {
                echo "Checking out"
            }
        }
        stage('Build and Test Java code') {
            steps {
				echo "Running build and testing Java code"
            }
        }
        stage('Build Docker images') {
            steps {
				echo "Building Docker image"
            }
        }
    }
}


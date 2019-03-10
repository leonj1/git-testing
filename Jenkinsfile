#!groovy

pipeline {
    tools { 
        maven 'maven 3.3.9' 
        jdk 'Java 1.8' 
    }
    environment {
        VERSION = '0.0.0'
    }

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


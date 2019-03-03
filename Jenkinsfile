pipeline {
    agent any
    stages {
        stage ('Compile Stage') {
            steps {
				echo "Compile stage running"
        		echo 'Pulling...' + env.GIT_BRANCH
        		checkout scm
            }
        }
        stage ('Testing Stage') {
            steps {
				echo "Testing stage running"
            }
        }
        stage ('Deployment Stage') {
            steps {
				echo "Deployment stage running"
            }
        }
    }
}

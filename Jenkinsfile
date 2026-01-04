pipeline {
    agent any 
    
    stages {
        stage('Preparation') {
            steps {
                echo 'Cleaning up workspace...'
                echo 'Downloading code...'
            }
        }
        stage('Build') {
            steps {
                echo 'Compiling the application...'
                sh 'sleep 5' 
            }
        }
        stage('boom') {
            steps {
                echo 'Running unit tests...'
                sh 'sleep 2' 
            }
        }
    }
}

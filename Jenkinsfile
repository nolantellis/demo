pipeline {
   agent {
        docker {
            image 'maven:3-alpine' 
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'mvn clean install'
            }
        }
        stage('Test') { 
            steps {
                 input "Deploy to prod?"
            }
        }
        stage('Deploy') { 
            steps {
                echo "deploy"
            }
        }
    }
}
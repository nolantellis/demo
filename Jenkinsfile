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
                echo "test" 
            }
        }
        stage('Deploy') { 
            steps {
                echo "deploy"
            }
        }
    }
}
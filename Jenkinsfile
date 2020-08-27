pipeline {
    agent any 
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
                echo "deplloy"
            }
        }
    }
}
pipeline {
    agent any
    stages {
        stage('AZ - Build Docker Image') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}
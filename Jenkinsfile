pipeline {
    agent any
    tools { 
        maven '3.9.8' 
    }
    stages {
        stage('AZ - Build Docker Image') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}
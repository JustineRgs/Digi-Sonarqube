pipeline {
    agent any
    tools {
        maven 'Maven 3.9.8'
    }
    stages {
        stage('checkout') {
            steps {
                git 'https://github.com/ScaleSec/vulnado'
            }
        }
        stage('checkout') {
            steps {
                sh 'mvn clean package' 
            }
        }
    }
}

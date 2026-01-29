pipeline {
    agent any

    tools {
        jdk 'Java11'
        maven 'Maven3'
    }

    stages {
        stage('Build') {
            steps {
                sh 'mvn clean compile'
            }
        }
        stage('Test') {
            steps {
                sh 'mvn test'
            }
        }
    }
}


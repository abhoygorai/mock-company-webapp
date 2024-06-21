pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                script {
                    // Build the application
                    sh './gradlew assemble'
                }
            }
        }
        stage('Test') {
            steps {
                script {
                    // Run tests
                    sh './gradlew test'
                }
            }
        }
    }
}

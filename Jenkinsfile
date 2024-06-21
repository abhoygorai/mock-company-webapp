pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                script {
                    // Build the application
                    bat './gradlew assemble'
                }
            }
        }
        stage('Test') {
            steps {
                script {
                    // Run tests
                    bat './gradlew test'
                }
            }
        }
    }
}

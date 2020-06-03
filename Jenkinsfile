pipeline {
    agent {
        dockerfile true
    }
    stages {
        stage('Test') {
            steps {
                sh './gradlew clean test --no-daemon'
            }
        }
    }
}
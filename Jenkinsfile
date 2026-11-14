pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                checkout scm
                echo 'hello wordd'
            }
        }
        stage('Hello') {
            steps { echo 'Hello from a Jenkinsfile stored in Git!' }
        }
    }
}
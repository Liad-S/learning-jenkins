pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                checkout scm
                echo 'hello wordd my name is Liad'
            }
        }
        stage('Hello') {
            steps { echo 'Hello from a Jenkinsfile stored in Git!' }
        }
    }
}
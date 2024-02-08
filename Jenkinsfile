pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                Checkout()
            }
        }
        stage('Build') {
            steps {
                Build()
            }
        }
        stage('Deploy') {
            steps {
                Deploy()
            }
        }
    }
}

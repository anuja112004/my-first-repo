pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'https://github.com/chaitumarar-dotcom/my-first-repo.git'
            }
        }
    
        stage('Built') {
            steps {
                echo 'Built'
                bat "javac java.java"
            }
        }
    
        stage('Test') {
            steps {
                echo 'Testing'
                bat "javac java.java"
            }
        }
   
        stage('Deploy') {
            steps {
                echo 'Deployment'
                bat "javac java.java"
            }
        }
    }
}

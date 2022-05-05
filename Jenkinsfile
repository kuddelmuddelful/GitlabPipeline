pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build'
                build 'Job1'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy'
                build 'Job2'
            }
        }
        stage('Test') {
            steps {
                echo 'Hello World'
                build 'Job3'
            }
        }
        stage('Release') {
            steps {
                echo 'Release'
            }
        }
        
    }

    
}

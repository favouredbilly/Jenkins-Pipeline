pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                 sh 'mvn clean install'
            }
        }
        stage('Test') {
            steps {
                echo 'Running Test Phase. Thanks.'
            }
        }
    }   
}
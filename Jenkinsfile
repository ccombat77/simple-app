pipeline {
    agent any
    tools {
        maven 'Maven'
    }
    stages{
        stage ('Compile') {
            steps {
                sh 'mvn clean compile'                              
            }
        }
        stage ('Testing') {
            steps {
                sh 'mvn test'                              
            }
        }
    }
}

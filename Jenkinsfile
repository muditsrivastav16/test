pipeline {
    agent {
            label 'Ubuntu'
        
    }
    
    stages {
        stage('compile') {
            steps {
                sh 'javac Demo.java'
            }
        }
        stage('Run') {
            steps {
                sh 'java Demo Ubuntu'
            }
        }
    }
}

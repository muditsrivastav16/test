pipeline {
    agent {
        node {
            label 'Ubuntu'
        }
    }
    
    stages {
        stage('compile') {
            steps {
                sh 'echo compiling'
            }
        }
        stage('Run') {
            steps {
                sh 'echo running'
            }
        }
    }
}

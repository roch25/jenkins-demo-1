pipeline {
    agent { label 'jenkins-slave-node-1'}

    stages {
        stage('Complete training') {
            steps {
                git branch 'dev'
            }
        }
        stage('Complete training') {
            steps {
                echo 'training'
            }
        }
         stage('Get to work') {
            steps {
                echo 'work'
            }
        }
        
         stage('Run index.js') {
            steps {
                bat 'node index.js'
            }
        }
    }
}

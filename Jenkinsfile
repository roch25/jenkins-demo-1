pipeline {
    agent { label 'jenkins-slave-node-1'}

    stages {
        stage('switch branch') {
            steps {
                git url:'https://github.com/roch25/jenkins-demo-1', branch: 'dev'
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

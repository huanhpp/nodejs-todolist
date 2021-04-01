pipeline {
    agent {
        label 'docker-agent'
    }
    stages {
        stage('Clone source code') {
            steps {
                git 'https://github.com/huanhpp/nodejs-todolist.git'
                sh 'ls'
            }
        }
    }
}
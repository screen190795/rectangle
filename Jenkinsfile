pipeline {
    agent any
    tools {
        maven 'Maven3'
    }
    stages {
        stage('Build') {
            steps {
                bat encoding: 'UTF-8', script: 'echo %PATH%'
            }
        }
    }
}

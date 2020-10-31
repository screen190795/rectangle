pipeline {
    agent any
    tools {
        maven 'Maven3'
    }
    stages {
        stage('Build') {
            steps {
                bat "mvn -B verify"
            }
        }
    }
}

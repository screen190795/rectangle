pipeline {
    agent any
    tools {
        maven 'Maven3'
    }
    stages {
        stage('Build') {
            steps {
                bat "${mvnHome}\\bin\\mvn -B verify"
            }
        }
    }
}

pipeline {
    agent any
    tools {
        maven 'Maven3'
    }
    stages {
        stage('Build') {
            steps {
                bat "${M3_HOME}\\bin\\mvn -B verify"
            }
        }
    }
}

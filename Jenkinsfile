pipeline {
    agent any
    tools {
        maven 'Maven3'
    }
    stages {
        stage('Build') {
             withMaven {
                  sh "mvn clean verify"
                }
        }
    }
}

pipeline {
    agent any
    triggers {
        githubPush()
    }
    stages {
        stage('Install') {
            steps { bat 'npm install' }
        }
        stage('Build') {
            steps { bat 'echo Build successful' }
        }
    }
}
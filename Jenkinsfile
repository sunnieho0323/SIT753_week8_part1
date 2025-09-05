pipeline {
    agent any
    stages {
        stage('Build') {
            steps { echo 'Run npm install to build project' }
        }
        stage('Unit & Integration Tests') {
            steps { echo 'Run npm test for unit and integration tests' }
        }
        stage('Code Analysis') {
            steps { echo 'Run ESLint to check code style and errors' }
        }
        stage('Security Scan') {
            steps { echo 'Run npm audit to find vulnerabilities' }
        }
        stage('Deploy to Staging') {
            steps { echo 'Simulate deploy: copy project to staging folder' }
        }
        stage('Integration Tests on Staging') {
            steps { echo 'Run npm test again on staging environment' }
        }
        stage('Deploy to Production') {
            steps { echo 'Simulate deploy: copy project to production folder' }
        }
    }
}

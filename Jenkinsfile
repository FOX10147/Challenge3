pipeline {
    agent none
    stages {
        stage('build') {
            agent any
            steps {
                sh "echo Building.............................."
            }
        stage('test') {
            agent any
            steps {
                sh "echo Testing..............................."
            }
        stage('deploy') {
            agent any
            steps {
                sh "echo Deploying............................."
            }
        }
        }
        }
    }
}
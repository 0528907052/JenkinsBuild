# JenkinsBuild
pipeline {
    agent any
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }    
        stage('Build') {
            steps {
                echo 'Run BUILD'
            }
        stage('Test') {
            steps {
                echo 'Run TEST'
            }    
        }
        stage('Post') {
            steps {
                echo 'By by'
            }
        }
    }
}

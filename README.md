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
        }
        stage('BY') {
            steps {
                echo 'By by'
            }
        }
    }
}

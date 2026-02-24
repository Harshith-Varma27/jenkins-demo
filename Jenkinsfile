pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                bat 'echo Building from GitHub Pipeline'
            }
        }

        stage('Run Python') {
            steps {
                bat 'python hello.py'
            }
        }
    }
}

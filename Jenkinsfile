pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Starting build ...'
                sh 'python welcome.py'
            }
        }
                stage('test') {
            steps {
                echo 'Starting test...'
                sh 'python welcome.py'
            }
        }
                stage('deploy') {
            steps {
                echo 'Starting deploy...'
                sh 'python welcome.py '
            }
        }
    }
}
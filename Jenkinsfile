pipeline {
    agent {
        docker {image 'python:3.7.2'}
    }
    stages {
        stage('Hello') {
            steps {
                cmd 'python main.py'
            }
        }
    }
}

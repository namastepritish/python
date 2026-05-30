pipeline {
    agent any
    stages {
        stage('version') {
            steps {
                sh 'python3 --version'
            }
        }        stage('hello world') {
            steps {
                sh 'python3 -c "print(\'Hello World\')"'
            }
        }
    }
}
pipeline {
    agent any
    stages {
        stage('version') {
            steps {
                sh 'python3 --version'
            }
        }        stage('hello first world') {
            steps {
                sh 'python3 -c "print(\'Hello World\')"'
            }
        }
    }
}
node {
    stage('version') {
        if (isUnix()) {
            sh 'python3 --version'
        } else {
            bat 'python --version'
        }
    }

    stage('hello first world') {
        if (isUnix()) {
            sh 'python3 -c "print(\'Hello World\')"'
        } else {
            bat 'python -c "print(\"Hello World\")"'
        }
    }
}
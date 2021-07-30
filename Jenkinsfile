pipeline {
    agent any
    stages {
        stage('BUILD') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps to work"
                    ls -ll
                '''
            }
        }
    }
}
pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
        stage('Build_More') {
            steps {
                sh 'echo "Hola Amigo"'
            }
        }
        stage('Build_continue_git') {
            steps {
                sh 'echo "Que Paso"'
            }
        }
    }
}

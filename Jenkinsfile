pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                 bat 'dir /a'
                 bat 'node --version'
                 bat 'npm --version'
                 bat 'npm install'
                 bat 'npm run build'
                 bat 'dir /a'                 
            }
        }
    }
}

pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                 bat 'dir /a'
                 bat 'node --version'
                 bat 'npm --version'
                 bat 'npm ci'
                 bat 'npm run build'
                 bat 'dir /a'                 
            }
        }
        stage('test'){
            steps{
                echo 'test stage'
            }
        }
    }
}

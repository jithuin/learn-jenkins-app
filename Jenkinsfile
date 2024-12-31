pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                 bat '''
                     dir /a
                     node --version
                     npm --version
                     npm ci
                     npm run build
                     dir /a 
                 '''
            }
        }
    }
}

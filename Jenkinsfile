pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                 bat '''
                     dir /a
                     node --version
                     npm --version
                     npm install 
                     npm run build
                     dir /a 
                 '''
            }
        }
    }
}

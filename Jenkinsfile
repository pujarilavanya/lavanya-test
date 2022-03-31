pipeline {
    agent none 
    stages {
        stage('install packages ') {
            steps {
                sh 'npm install'
            }
        }
        stage('Example Test') {
            steps {
                sh 'npm run build --prod'
            }
        }
    }
}

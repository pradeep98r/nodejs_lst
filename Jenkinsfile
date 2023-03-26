pipeline {
    agent any
    
    stages {
        stage('Deploy') {
            steps {
                git 'https://github.com/pradeep98r/nodejs_lst.git'
                sh 'cd node-app && npm install'
                sh 'cd node-app && node index.js'
            }
        }
    }
}

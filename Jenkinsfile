pipeline {
    agent any
    
    stages {
        stage('Deploy') {
            steps {
                git 'https://github.com/pradeep98r/nodejs_lst.git'
                sh 'cd nodejs_lst && npm install'
                sh 'cd nodejs_lst && node index.js'
            }
        }
    }
}

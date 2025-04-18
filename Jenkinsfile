pipeline {
    agent any
    tools {
        nodejs 'nodejs-23'
    }
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}

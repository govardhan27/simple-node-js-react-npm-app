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
    stage('Test') { 
            steps {
                sh './jenkins/scripts/test.sh' 
            }
        }
    }
}

pipeline {
    agent {
        kubernetes {
            label jenkins-jnlp-agent-node
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}

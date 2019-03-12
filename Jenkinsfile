pipeline {
    agent { node { label 'node-react' }  
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}

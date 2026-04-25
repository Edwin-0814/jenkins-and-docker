pipeline {
    agent any
    stages {
        stage('Build & Push') {
            steps {
                sh 'docker build -t edwinpaul23/app5:latest .'
                sh 'docker push edwinpaul23/app5:latest'
            }
        }
    }
}

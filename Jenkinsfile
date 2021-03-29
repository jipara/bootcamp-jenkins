pipeline {
    agent any
    stages {
        stage('Stage 1') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/jipara/bootcamp-hw.git'
            }
        }
        stage('stage 2') {
            steps {
                sh 'terraform init'
                sh 'terraform apply -auto-approve'
            }
        }
    }
}
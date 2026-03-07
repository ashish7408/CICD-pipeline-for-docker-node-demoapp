pipeline {
    agent any

    stages {

        stage('Clone Repository') {
            steps {
               git branch: 'main', url: 'https://github.com/ashish7408/docker-node-demo.git'
            }
        }

        stage('Build Docker Image') {
            steps {
                bat 'docker build -t devops-demo .'
            }
        }

        stage('Run Container') {
            steps {
                bat 'docker run -d -p 3000:3000 devops-demo'
            }
        }

    }
}

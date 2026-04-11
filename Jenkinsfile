pipeline {
    agent any

    stages {

        stage('Build Docker Image') {
            steps {
                sh 'docker build -t surya-demo .'
            }
        }

        stage('Run Container') {
            steps {
                sh 'docker run surya-demo'
            }
        }

    }
}

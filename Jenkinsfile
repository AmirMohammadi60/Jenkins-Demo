pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Maven  Package'
            }
        }
        stage('Test') {
            steps {
                echo 'Maven test'
            }
        }
        stage('Run') {
            steps {
                echo 'Maven running'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}

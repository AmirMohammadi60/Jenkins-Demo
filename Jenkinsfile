pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'mvn package'
            }
        }
        stage('Test') {
            steps {
                echo 'mvn test'
            }
        }
        stage('Run') {
            steps {
                echo 'mvn running'
            }
        }
        stage('Deploy') {
            steps {
                archiveArtifacts artifacts: '**/target/*.jar, fingerprint: true'
            }
        }
    }
}

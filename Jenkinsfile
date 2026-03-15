pipeline {
    agent any

    stages {

        stage('Clone Stage') {
            steps {
                echo 'Repository cloned successfully'

            }
        }

        stage('Build Stage') {
            steps {
                bat 'echo Building project'
            }
        }

        stage('Test Stage') {
            steps {
                bat 'echo Running tests'
            }
        }

    }
}
pipeline {
    agent any

    stages {

        stage('Clone Stage') {
            steps {
                echo 'Repository cloned successfully'
                ,  url: 'https://github.com/Ratna-Tej/jenkins-test.git',
                    credentialsId: 'github-creds'
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

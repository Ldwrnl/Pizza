pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building'
                git 'https://github.com/Ldwrnl/Pizza'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing'
            }
        }
        stage('Release') {
            steps {
                echo 'Releasing'
            }
        }
    }
}

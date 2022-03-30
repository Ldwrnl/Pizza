pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building'
                git 'https://github.com/Ldwrnl/Pizza'
                git install
                git clone 'https://github.com/Ldwrnl/Pizza'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying'
                // npm install -- global surge
                // surge --project ./public --domain https://besterpizzatimerever.surge.sh/
                
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

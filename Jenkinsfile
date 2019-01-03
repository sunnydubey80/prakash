pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'git clone https://github.com/sunnydubey80/prakash.git'
                sh 'docker build -t sundocker12345/test -f Dockerfile .'
                sh 'docker push sundocker12345/test'
                sh 'ls' 
                sh 'pwd'
                sh 'rm -rf prakash' 
            }
        }
    }
}
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'rm -rf prakash'
                sh 'git clone https://github.com/sunnydubey80/prakash.git'
                sh 'docker build -t sundocker12345/test:${BUILD_NUMBER} -f Dockerfile .'
                sh 'docker push sundocker12345/test:${BUILD_NUMBER}
                sh 'ls' 
                sh 'pwd' 
            }
        }
    }
}

pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Test Connection') {
            steps {
                echo 'GitHub 저장소 연결 성공!'
            }
        }
    }
}


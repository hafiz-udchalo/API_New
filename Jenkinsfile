pipeline {
    agent any
    environment {
        HAFIZ = credentials('Hafiz')
        WEB = credentials('GOOGLE')
        PING = credentials('PING')
    }
    stages {
        stage('Example stage 1') {
            steps {
                echo "Welcome"
                echo "${HAFIZ}"
                sh "uptime"
                sh 'ping "${PING}"'
            }
        }
    }
}

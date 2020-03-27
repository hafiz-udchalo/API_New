pipeline {
    agent any
    environment {
        HAFIZ = credentials('Hafiz')
        WEB = credentials('GOOGLE')
    }
    stages {
        stage('Example stage 1') {
            steps {
                echo "Welcome"
                echo "${HAFIZ}"
                sh "uptime"
                sh 'cat "${WEB}"'
                sh 'ping "${PING}"'
            }
        }
    }
}

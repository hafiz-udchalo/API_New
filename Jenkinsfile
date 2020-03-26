pipeline {
    agent any
    environment {
        HAFIZ = credentials('Hafiz')
    }
    stages {
        stage('Example stage 1') {
            steps {
                echo "Welcome"
                echo "${HAFIZ}"
            }
        }
    }
}

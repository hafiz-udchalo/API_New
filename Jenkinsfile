pipeline {
    agent {
        // Define agent details here
    }
    environment {
        HAFIZ = credentials('Hafiz')
    }
    stages {
        stage('Example stage 1') {
            steps {
                sh echo "Welcome"
                sh echo "${HAFIZ}
            }
        }
        stage('Example stage 2') {
            steps {
                // 
            }
        }
    }
}

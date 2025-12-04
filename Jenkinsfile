pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git url: 'https://github.com/<username>/jenkins-test-pipeline.git', branch: 'main'
            }
        }

        stage('Build') {
            steps {
                echo "Eseguo una build di test..."
            }
        }

        stage('Test') {
            steps {
                echo "Eseguo test di esempio..."
            }
        }

        stage('Deploy') {
            steps {
                echo "Finto deploy eseguito"
            }
        }
    }
}

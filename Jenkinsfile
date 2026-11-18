pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Build en cours...'
            }
        }
        stage('Test') {
            steps {
                echo 'Tests en cours...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Déploiement en cours...'
            }
        }
    }
    post {
        success { echo 'Pipeline réussi' }
        failure { echo 'Pipeline en échec' }
    }
}

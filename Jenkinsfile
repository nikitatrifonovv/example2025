pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/nikitatrifonovv/example2025.git'
            }
        }

        stage('Build') {
            steps {
                sh 'echo Сборка приложения'
            }
        }

        stage('Test') {
            steps {
                sh 'echo Запуск тестов'
            }
        }
    }
}

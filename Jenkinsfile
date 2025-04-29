pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/BanafshaPatel/devops_prac.git'
            }
        }
        stage('Install Dependencies') {
            steps {
                echo 'No dependencies to install'
            }
        }
        stage('Test') {
            steps {
                echo 'Running test stage...'
            }
        }
    }
}

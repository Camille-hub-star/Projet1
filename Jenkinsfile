pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/Camille-hub-star/Projet1.git'
            }
        }

        stage('Build') {
            steps {
                sh 'mvn clean install'
            }
        }

        stage('Test') {
            steps {
                sh 'mvn test'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Déploiement fictif terminé.'
            }
        }
    }
}

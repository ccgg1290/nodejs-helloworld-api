pipeline {
    agent any
    tools {
        nodejs 'nodejsprueba'
    }
    stages {
        stage('Build') {
            steps {
                echo "Ejecutar npm instal" 
                sh 'npm install'
            }
        }

        stage('Test') {
            steps {
                echo "Ejecutar npm test push" 
                sh 'npm test'
            }
        }
    }
}

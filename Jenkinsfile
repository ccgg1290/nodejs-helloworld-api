pipeline {
    agent any
    tools {
        nodejs 'nodejsprueba'
    }
    stages {
        stage('Build') {
            steps {
                echo "Ejecutar npm installl" 
                sh 'npm instal'
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

pipeline {
    agent any
    tools {
        nodejs 'nodejs21'
    }
    stages {
        stage('Build') {
            steps {
                echo "Ejecutar npm installl" 
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

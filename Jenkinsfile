pipeline {
    agent any
    stages {
        stage('Check Docker') {
            steps {
                script {
                    // Verificar la versión de Docker
                    sh 'docker --version'
                    
                    // Verificar los contenedores en ejecución
                    sh 'docker ps'
                }
            }
        }
    }
}

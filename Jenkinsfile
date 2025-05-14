pipeline {
    agent any

    stages {
        stage('Clonar código') {
    steps {
        git branch: 'main', url: 'https://github.com/Olaya177/Ejemplo_automatizacion.git'
    }
}

        stage('Compilar') {
            steps {
                bat 'javac MiClase.java'
            }
        }
        stage('Ejecutar') {
            steps {
                bat 'java MiClase'
            }
        }
    }
}

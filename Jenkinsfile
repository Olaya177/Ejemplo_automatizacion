pipeline {
    agent any

    stages {
        stage('Clonar código') {
            steps {
                git 'https://github.com/Olaya177/Ejemplo_automatizacion.git'
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

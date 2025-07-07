pipeline {

    agent any

    // escenarios -> escenario -> pasos

    stages{
        stage ("saludo a usuario") {
            steps {
                sh 'echo "hola a todos desde el pipeline"'
                sh 'echo "saliendo del pipeline"'
            }
        }
    }
}
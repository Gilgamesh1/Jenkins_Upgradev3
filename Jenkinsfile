pipeline{
    agent any
    stages{
        stage('Init'){
            steps{
                echo 'Hi, this is Raul Llerena '
                echo 'Iniciando pruebas...'
            }
        }
        stage('Build'){
            steps{
                echo 'Construyendo la Aplicacion Maven...'
            }
        }
        stage('Deploy'){
            steps{
                echo 'Deplegando la aplicacion.....'
                echo 'Yeahh Baby...'
            }
        }
        stage('Deploy Production'){
            steps{
                echo 'Deplegando la aplicacion en Produccion.....'
                for(int i=0; i<5 ; i++) {
                    echo 'Yeahh Baby...'
                }
            }
        }
    }
}
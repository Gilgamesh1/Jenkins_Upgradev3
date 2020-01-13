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
                0.step 5,1, {
                    echo '2(Yeahh Baby...)'
                }
            }
        }
    }
}
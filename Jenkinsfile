pipeline{
    agent any
    stages{
        stage('IBuild Image') {
            steps {
                script{
                    dockerapp = docker.build("mvcardim/apweb_docker", '-f ./docker-compose ./')
                }
                echo 'iniciando a pipeline'
            }
        }
    }
}
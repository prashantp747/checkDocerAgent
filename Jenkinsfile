pipeline{

    agent {
    docker {
    args '-p 8989:8989'
    image 'mongo-express:0.54.0'
        }
    }

    stages{
        stage("build") {
            steps {

                sh 'echo *************************'
                sh 'node --version'
                sh 'npm -v'
                sh 'mongod --version'
                               
            }
        }

    }
}
pipeline{

    agent {
    docker {
    args '-p 8989:8989'
    image 'node:12.22.1'
        }
    }

    stages{
        stage("build") {
            steps {

                sh 'echo *************************'
                sh 'node --version'
                sh 'npm -v'
                               
            }
        }

    }
}
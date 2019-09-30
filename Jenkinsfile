pipeline {
    agent any

    stages {
        stage('Getting Dependencies') {
            steps {
                echo 'Building..'
                pwd
                uname -a
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}

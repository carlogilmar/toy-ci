pipeline {
    agent any

    stages {
        stage('Getting Dependencies') {
            steps {
                echo 'Building..'
                mix deps.get
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

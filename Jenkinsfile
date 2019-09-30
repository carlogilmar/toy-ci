pipeline {
    agent any

    stages {
        stage('Getting Dependencies') {
            steps {
                echo 'Running bash..'
                sh '''#!/bin/bash
                echo "hello world"
                pwd
                uname -a
                '''
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

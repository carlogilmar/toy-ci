pipeline {
    agent any

    stages {
        stage('Getting Dependencies') {
            steps {
                echo 'Building..'
                bash '''#!/bin/bash
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

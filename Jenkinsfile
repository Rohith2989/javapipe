pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Build and Test') {
            steps {
               bat '"C:\\Maven\\apache-maven-3.10.0\\bin\\mvn.cmd" clean package'
            }
        }
    }
}
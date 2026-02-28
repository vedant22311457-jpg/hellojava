pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/vedant22311457-jpg/hellojava.git'
            }
        }

        stage('Build') {
            steps {
                bat 'javac HelloWorld.java'
            }
        }

        stage('Run Program') {
            steps {
                bat 'java HelloWorld'
            }
        }
    }
}

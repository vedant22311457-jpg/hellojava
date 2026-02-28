pipeline {
    agent any

    stages {
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

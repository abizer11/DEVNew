pipeline {
    agent any

    stages {
        stage('Build Java App') {
            steps {
                bat 'javac HelloWorld.java'
            }
        }

        stage('Run Java App') {
            steps {
                bat 'java HelloWorld'
            }
        }

        stage('Run Python App') {
            steps {
                bat 'python hello.py'
            }
        }
    }
}

pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                dir('src/main/java') {
                    sh 'javac HelloWorld.java'
                }
            }
        }

        stage('Test') {
            steps {
                dir('src/main/java') {
                    sh 'src/main/java HelloWorld'
                }
            }
        }
    }
}

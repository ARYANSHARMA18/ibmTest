pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                dir('src/main/java') {
                    bat 'javac HelloWorld.java'
                }
            }
        }
    }
}

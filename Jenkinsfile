pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('BUILD') {
            steps {
                echo 'DEV'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing'
            }
        }
        stage('DEPLOY') {
            steps {
                echo 'Mise en production'
            }
        }
    }
}

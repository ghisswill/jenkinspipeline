pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
    }
    stages {
        stage('BUILD') {
            steps {
                echo 'DEV'
            }
        }
    }
    stages {
        stage('Test') {
            steps {
                echo 'Testing'
            }
        }
    }
    stages {
        stage('DEPLOY') {
            steps {
                echo 'Mise en production'
            }
        }
    }
}

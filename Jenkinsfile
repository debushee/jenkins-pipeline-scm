pipeline {
    agent any

    stages {
        stage('Clean') {
            steps {
                cleanWs()
            }
        stage('Hello') {
            steps {
                git branch: 'main', url: 'https://github.com/debushee/jenkins-pipeline.git'
                echo 'Hello World'
                sh 'mkdir MyScript1'
            }
        }
        stage('Goodbye') {
            steps {
                echo 'Woteva'
            }
        }
    }
}

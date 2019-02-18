pipeline {
    agent any
    stages {
        stage('Build') {
            steps { 
                composer install
        stage('myStage'){
            steps {
                bat 'dir'
            }
        }
        stage('Build') {
            steps { 
                bat 'dir' 
            }
        }
    }
}

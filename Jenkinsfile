pipeline {
    agent any
    
    

    stages {
    
    stage('SCM checkout'){
        git 'https://github.com/dineshreddy6461/mavendin'
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}

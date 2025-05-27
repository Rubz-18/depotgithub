pipeline {
    agent any
    
    stages {
        stage('HELLO') {
            steps {
                echo 'HELLO WORLD'
                
            }
        }
        stage('Checkout SCM GITHUB'){
            steps {
                deleteDir()
                git branch: 'main', credentialsId: 'user-github', url: 'https://github.com/Rubz-18/depotgithub.git'
            }
        }
    }
}

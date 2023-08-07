pipeline {
    agent any
    
    environment {
        Name= "capgemini"
    }
    
    stages {
        stage ('env') {
            steps {
                git branch: 'main', credentialsId: 'git-creds', url: 'https://github.com/bkaarthic/demo.git'
            }
        }
    }
}

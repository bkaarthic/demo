pipeline {
    agent any
    
    environment {
        Name= "cytiva"
    }
    
    stages {
        stage ('env') {
            steps {
                git branch: 'main', credentialsId: 'git-creds', url: 'https://github.com/bkaarthic/demo.git'
            }
        }
    }
}

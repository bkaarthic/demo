pipeline {
    agent any
    
    environment {
        Name= "capgemini"
    }
    
    stages {
        stage ('env') {
            steps {
                sh 'echo "$Name"'
            }
        }
    }
}

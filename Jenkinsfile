pipeline {
    environment {
        var1 = "variable1"
    }
    agent any
    stages {
        stage('first') {
            steps {
                sh 'rm -rf *'
                sh 'git clone https://github.com/jenkinsdemos/antbuildexample.git .'
                sh 'ant'
                
            }  
            
        }
    }
    
}

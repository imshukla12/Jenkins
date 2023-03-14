pipeline {
    agent any
 
    stages {
        stage('Clone Git') {
            steps {
                git 'https://github.com/imshukla12/Jenkins.git'
            }
        }
        stage('Build Code') {
            steps {
                sh "chmod u+x prog1.py"
                sh "./prog1.py" 
            }
        }
        stage('test code') {
            steps {
                sh "chmod u+x prog1.py"
                sh "./prog1.py"
            }
        }
        
    }
}

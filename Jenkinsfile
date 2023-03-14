pipeline {
    agent any
    stages {
        stage('Clone Git') {
            steps {
                git url: 'https://github.com/imshukla12/Jenkins.git' , branch: 'main'
            }
        }
        stage('Build Code') {
            steps {
                sh "sudo chmod u+x prog1.py"
                sh "./prog1.py" 
            }
        }
        stage('test code') {
            steps {
                sh "sudo chmod u+x test.py"
                sh "./test.py"
            }
        }
        
    }
}

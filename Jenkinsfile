pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                git 'https://github.com/nissimlidan/MySoftware.git' 
                bat 'python master.py'
            }
        }
    }
}

pipeline {
    agent any
    stages {
        stage('run') {
            steps {
                echo 'Dogan_Way to Reinvent Yourself'
                sh 'python --version'
		        sh 'python hello-world.py'
                sh 'python pipeline.py'
            }
        }
    }
}

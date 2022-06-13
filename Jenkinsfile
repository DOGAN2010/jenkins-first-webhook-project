pipeline {
    agent any
    stages {
        stage('run') {
            steps {
                echo 'Dogan_Way to Reinvent Yourself'
                sh 'python3 --version'
		        sh 'python3 hello-world.py'
                sh 'python3 pipeline.py'
            }
        }
    }
}

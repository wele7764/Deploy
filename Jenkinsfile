pipeline {
    agent any 
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
				git 'https://github.com/wele7764/Deploy/test.py.git'
            }
        }
		stage('Python test') {
            steps {
                sh 'python3 test.py'
            }
        }
    }
}

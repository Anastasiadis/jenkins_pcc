pipeline {
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('stage1') {
            steps {
                sh 'python --version'
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
		  }        
		}
        }
}

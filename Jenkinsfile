Jenkinsfile (Declarative Pipeline)
pipeline {
    agent { docker { image 'python:3.7.0' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
	post{
		always {
			echo 'This should always echo'
		}
	}	
			
}

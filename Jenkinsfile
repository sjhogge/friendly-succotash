Jenkinsfile (Declarative Pipeline)
pipeline {
    agent { docker { image 'python:3.5.1' } }
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

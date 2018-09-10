Jenkinsfile (Declarative Pipeline)
pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'make'
            }
        }
    }
	post{
		always {
			echo 'This should always echo'
		}
	}	
			
}

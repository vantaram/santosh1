pipeline {
    agent any

    tools {
        maven 'maven'
    }

    stages {
        stage('Build') {
            steps {
                git branch: 'main', url: 'https://github.com/ksrepo9/kartikeyapro.git'
                   }
			            }
		stage('maven clean') {
            steps {
                sh 'mvn clean'
                   }
			            }
		stage('maven test') {
            steps {
                sh 'mvn test'
                   }
			            }
		stage('mave compile') {
            steps {
                sh 'mvn compile'
                   }
			            }
		stage('maven package') {
            steps {
                sh 'mvn package'
                   }
			            }
		stage('maven deployment') {
            steps {
                sh 'mvn deployment'
                   }
			            }
			}			
	}
	

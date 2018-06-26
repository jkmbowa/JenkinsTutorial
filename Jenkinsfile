pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Build starting'
				sh 'gradle build --info'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing Build'
            }
        }

    }
}
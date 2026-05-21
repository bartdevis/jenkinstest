pipeline {
    agent any

    
    stages {
         stage('Build WAR') {
            steps {
                sh 'gradlew build'
            }
         }

        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}

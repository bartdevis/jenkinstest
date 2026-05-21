pipeline {
    agent any

    
    stages {
         stage('Build WAR') {
            steps {
                sh 'mvn clean package -DskipTests'
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

pipeline {
    agent { label 'anand' }

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
              sh 'pm2 start "ng serve" --name angular-jenkins'
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

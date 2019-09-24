pipeline {
    agent { label 'anand' }

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
              sh 'ng serve'
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

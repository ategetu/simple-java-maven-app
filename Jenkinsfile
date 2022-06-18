pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Build Apps'
            }
        }
        stage('Test') {
            steps {
                echo 'Test Apps'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy Apps'
            }
        }
    }

post
{
always
{emailext body:'Summary', subject:'pipeline status', to: 'atasahalu28@gmail.com'
}
}
}

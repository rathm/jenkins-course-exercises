pipeline {
    agent any
    stages {
        stage('CHECKOUT') {
            steps {
                checkout([$class: 'GitSCM', branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: '5d4ea237-97a0-4507-9e7f-ad2af0415744', url: 'https://github.com/rathm/jenkins-course-exercises.git']]])
            }
        }
        stage('STAGE 2') {
            steps {
                echo 'Hello Menachem!'
            }
        }
    }
}

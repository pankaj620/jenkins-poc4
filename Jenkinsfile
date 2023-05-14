
pipeline {
    agent any
    //triggers {
cron('*/1 * * * *')
}
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        
        stage('Deploy') {
            steps {
                echo 'Welcome to Jenkins'
            }
        }
    }
}

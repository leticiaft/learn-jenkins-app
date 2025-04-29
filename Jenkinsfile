pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Hello World'
            }
        }

        stage('Test') {
            steps {
                sh 'test -f build/index.html'
            }
         }    
    }
}

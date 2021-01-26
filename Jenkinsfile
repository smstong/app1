pipeline {
    agent any
    //triggers { pollSCM('* * * * *') }

    stages {
    /*
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/smstong/app1.git'
            }
        }
    */
        stage('Build') {
            steps {
                sh 'make'
            }
        }
    }
}

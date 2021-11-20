pipeline {
    agent {node { label 'linux' }}

    stages {
        stage('Hello') {
            steps {
            sh '''
                echo 'Hello World zeeshan' > zeeshan.txt
                hostname
            '''
            }
        }
        stage('faraz') {
            steps {
                echo 'Hello World faraz'
            }
        }        
    }
}

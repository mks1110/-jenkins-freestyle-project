pipeline {

    agent any

    stages {

        stage('Build') {

            steps {

                sh 'echo "Building..."'

                sh 'ls -al'

            }

        }

        stage('Test') {

            steps {

                sh 'echo "Testing..."'

                sh 'pwd'

                sh 'touch testfile.txt'

                sh 'ls -l'

            }

        }

        stage('Deploy') {

            steps {

                echo "hello world"

            }

        }

    }

}
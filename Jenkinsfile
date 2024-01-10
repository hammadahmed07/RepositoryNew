pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Checkout the Git repository
               https://github.com/hammadahmed07/RepositoryNew.git
            }
        }

        stage('Build') {
            steps {
                // You can include build commands here if necessary
                // For example: sh 'mvn clean install'
              echo 'Build App'
            }
        }

        stage(' Test App') {
            steps {
                // Run your test cases
                // For example: sh 'mvn test'
               echo 'Test App'
            }
        }
       stage('Deploy App') {
            steps {
                // Run your test cases
                // For example: sh 'mvn test'
               echo 'Deploy App'
            }
        }
    }

    post {
        always {
            // Cleanup steps, if any
        }
        success {
            // Steps to execute if the pipeline is successful
        }
        failure {
            // Steps to execute if the pipeline fails
        }
    }
}


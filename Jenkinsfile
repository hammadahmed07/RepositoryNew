pipeline
 {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build App'
            }
        }
	stage('Test') {
            steps {
                echo 'Test App'
            }
        }
   	stage('Deply') {
            steps {
                echo 'Deploy App'
            }
        }
   
    }
post {
	always
	{
		emailext body: 'Summary' , subject: 'Pipeline Status', to: 'hamyahmed007@gmail.com'
	}
}

}

pipeline { 
    agent any

    stages {

        stage('Run Script') {
            steps {
                sh 'chmod +x helloworld.sh'
                sh './helloworld.sh'
            }
        }
    }
}

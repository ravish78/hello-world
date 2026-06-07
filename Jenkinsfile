pipeline { 
    agent any

    stages {

        stage('Checkout Code') {
            steps {
                git 'https://github.com/ravish78/hello-world.git'
            }
        }

        stage('Run Script') {
            steps {
                sh 'chmod +x helloworldcode.sh'
                sh './helloworldcode.sh'
            }
        }
    }
}

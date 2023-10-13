pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Checkout your source code from the repository.
                checkout([
                    $class: 'GitSCM',
                    branches: [[name: '*/main']], // You can specify the branch you want to build here.
                    userRemoteConfigs: [[url: 'https://github.com/Mohamed-Rouahi/Project-devops.git']]
                ])
            }
        }
         stage('Email Notification'){
             mail bcc: '', body: 'testing email notfication', cc: '', from: '', replyTo: '', subject: 'Jenkins', to: 'mohamed.rouahi@esprit.tn'
        // Add more stages for building, deployment, etc. as needed.
    }

}



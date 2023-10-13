node{
    stage('SCM Checkout'){
        git 'https://github.com/Mohamed-Rouahi/Project-devops.git'  
    }
    stage('Email Notification'){
        mail bcc: '', body: 'azza ya jabreya email', cc: '', from: '', replyTo: '', subject: 'Jenkins', to: 'azza.kouka@esprit.tn'        
    }

}

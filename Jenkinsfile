node{
    stage('SCM Checkout'){
        git 'https://github.com/Mohamed-Rouahi/Project-devops.git'  
    }
    stage('Email Notification'){
        mail bcc: '', body: 'testing email notfication', cc: '', from: '', replyTo: '', subject: 'Jenkins', to: 'mohamed.rouahi@esprit.tn'        
    }

}

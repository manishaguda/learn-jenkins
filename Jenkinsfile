pipeline {

  agent {
     label 'ansible'
  }

  stages {

    stage('Hello') {
      steps {
        echo 'Hello World'
      }
   }

   stage('Hello1') {

      steps {
        echo 'Hello World'
    }
  }

  stage('Hello2') {
     steps {
        echo 'Hello World'
        mail bcc: '', body: 'Hello this is test mail', cc: '', from: '', replyTo: '', subject: 'test', to: 'manishavguda@gmail.com'
     }
  }

}

  post {
     always {
       echo "sending email"
     }


     }
  }





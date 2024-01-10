pipeline {
   agent any
   stages {
       stage('Hello') {
           steps {
               echo "Hello beatiful world"
                   }
           }
       }
   post{
       always{
           mail to: "kkelebeklersonsuzaucar@gmail.com",
           subject: "Test Email",
           body: "Test"
       }
   }
}

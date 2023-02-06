pipline{
    agent{
       label{
           label "built-in"
       }
     }
     
   stages{
      stage('install apache'){
         steps{
           sh "yum install httpd -y"
           sh "service httpd start"
           sh "yum update -y"

               }

          }

   }
}

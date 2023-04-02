pipeline{
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
           sh "echo 'hello world' >> /var/www/html/index.html"
           sh "chmod -R 777 /var/www/html/index.html"
               }

          }

   }
}

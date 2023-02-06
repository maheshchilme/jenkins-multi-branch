pipline{
    agent{
       label{
           label "qa"
       }
     }
     
   stages{
      stage('install apache'){
         steps{
           sh "yum install httpd -y"
           sh "service httpd start"
           echo "hello world" >>/var/www/html/index.html
           chmod -R 777 /var/www/html/index.html
           

               }

          }

   }
}

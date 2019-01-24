# Wordpress-with-Docker
Create a wordpress with docker
 
 
 Hub.docker.com
 
 Mysql 
 
 CreeCreeate new user and password
 CramCreate new phpmyadmin
   
   
   Version :'3'
   
   
   Servicea:
   #database
   Db:
   Image :mysql 
   Volume:
   Reztart :always
   Environment 
   Mysql root 
   Myzql user
   Mysql password
   
   
   #wordpress
   
   
   Wordpress
   Depends on
   Image 
   Port
   Restart 
   Volume 
   Environment 
      Host
      User
      Password 
      
    Network-wpsite
    
   Network:   
   Wp-site
   Volume:
   Db-data
   
      
   
   
   

# my-docker-project
A simple docker project of containerize the docker containers by docker compose file to dockerize webserver using nginx and php

# systemctl start docker

# vim docker.yml
                          you can use any name but default name is docker-compose.yml 
                          we can -f to use different name
      
use the docker.yml for the code

# docker-compose -f docker.yml config   
                           To check any error  it will show the entire code to you if there is no mistake.

# docker-compose -f  docker.yml up -d 
                           -d to run in it background

# #localhost:8081  
                           now use your ip address:port no  or use  
                             you can see the web page

 # localhost:8081/info.php
                            To see the php is working or not

 congratulation ! you done it.

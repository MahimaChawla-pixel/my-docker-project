# my-docker-project
A simple docker project of containerize the docker containers by docker compose file to dockerize webserver using nginx and php

1..systemctl start docker

2..vim docker.yml
                          #you can use any name but default name is docker-compose.yml 
                          #we can -f to use different name
      
use the docker.yml for the code

3..docker-compose -f docker.yml config   
                           # To check any error  it will show the entire code to you if there is no mistake.

4..docker-compose -f  docker.yml up -d 
                           # -d to run in it background

5..now use your ip address:port no  or use localhost:8081    
                             #you can see the web page

6..To see the php running  localhost:8081/info.php

 congratulation ! you done it.

## Pre-Requisite  ##
#### Windows ####
    Open C:\Windows\System32\drivers\etc\hosts file in notepad and add below 2 lines
    
    127.0.0.1		service-registry2
    127.0.0.1		service-registry1

## EUREKA ##
Eureka we run in peer mode(2 servers), so it will act both as Client and Server.

#### Service Registry 1 ####
-Dspring.profiles.active=service-registry1 

http://localhost:8761/

#### Service Registry 2 ####
-Dspring.profiles.active=service-registry2 

http://localhost:8762/


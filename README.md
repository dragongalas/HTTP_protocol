# HTTP-1.0_protocol
## To init project
  1. Write make to execute makefile
  2. Launch executable server and pick a port 
  HTTP default port should be 80, but Ports 1024 and below are Privileged Ports
  Ports above 1024 are Emphemeral Ports.
  
 ## To use
  1. Launch client by using IP=0.0.0.0 and the same port that server uses
  2. Write a request Example: HEAD /docs/index.html HTTP/1.0
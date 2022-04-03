# Task15
Riemann Tasks

1) Who monitors the monitor ?

Based on your understanding of the monitoring stack  

identify what could break monitoring 

will you be able to identify when component within monitoring stack goes down. If so how - how can you bring redundancy here  
  
You can give a writeup ( use diagrams if you like to convey better ) 

2) Setup Riemann 
- bring up toy riemann server whose job is to print/log events to stdout as events come. 
- write a plugin/script in a language of your choice to monitor server load avg every min and send as event to riemann (Clients are available  https://riemann.io/clients.html)  
- setup riemann-dashboard that displays riemann's index (in memory state of current events) and create a dashboard to see load event being sent (https://riemann.io/dashboard.html) 
 
 - See if you can combine Riemann server and Riemann dash installation as docker container.

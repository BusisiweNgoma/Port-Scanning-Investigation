# Port-Scanning-Investigation
Using Zenmap to identify open ports and investigate running services on a local machine

In this exercise, I used Zenmap to scan my local machine and identfy open ports. The goal was to understand which services were running and how to trace them back to the processes responsible. 

Tools 
Zenmap
Nmap
Windows Command Prompt
Task Manager

Findings
The scan revealed 3 open ports:
135 - Windows RPC service
445 - Windows file sharing
6789 - Elastic agent used for log monitoring

I used the nestat - ano command to identify the PID linked to port 6789 and then confirmed the running process through Task Mnanager (I only investigated port 6789 because I was unfarmiliar with it)

this small investigaiton helped me undersand how analysis identify open ports and trace them back to running services during basic analysis 

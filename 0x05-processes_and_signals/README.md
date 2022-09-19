# 0x05. Processes and signals

## Tasks
___________________________________________________________
**0. What is my PID**
- Write a Bash script that displays its own PID.
___________________________________________________________
**1. List your processes**
- Write a Bash script that displays a list of currently running processes.
___________________________________________________________
**2. Show your Bash PID**
- Using your previous exercise command, write a Bash script that displays lines containing the bash word, thus allowing you to easily get the PID of your Bash process
__________________________________________________________
**3. Show your Bash PID made easy**
- Write a Bash script that displays the PID, along with the process name, of processes whose name contain the word bash.
_________________________________________________________
**4. To infinity and beyond**
- Write a Bash script that displays To infinity and beyond indefinitely.
_________________________________________________________
**5. Don't stop me now!**
- We stopped our 4-to_infinity_and_beyond process using ctrl+c in the previous task, there is actually another way to do this.
_________________________________________________________
**6. Stop me if you can**
- Write a Bash script that stops 4-to_infinity_and_beyond process.
_________________________________________________________
**7. Highlander**  
- Write a Bash script that displays:  
  
   To infinity and beyond indefinitely  
   With a sleep 2 in between each iteration  
   I am invincible!!! when receiving a SIGTERM signal
_________________________________________________________
**8. Beheaded process**
- Write a Bash script that kills the process 7-highlander.
_________________________________________________________
**9. Process and PID file**
- Write a Bash script that:  
  
   Creates the file /var/run/myscript.pid containing its PID  
   Displays To infinity and beyond indefinitely  
   Displays I hate the kill command when receiving a SIGTERM signal  
   Displays Y U no love me?! when receiving a SIGINT signal  
   Deletes the file /var/run/myscript.pid and terminates itself when receiving    a SIGQUIT or SIGTERM signal
   ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/9/d8ecfe9109334898b9540ffd20cf64d1c06f0c09.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220919%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220919T135219Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=9ad087648127cc1ca7d506182860b21f0bd4eedd45247f34a051b831eea9b8ad)
_______________________________________________________  


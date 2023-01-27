# Processes and signals                                                                                                                                         

                                                                                                                                                                

In this project, I learned about handling process ID's and signals in Bash with `ps`, `pgrep`, `pkill`, `pkill`, `exit`, and `trap`.                            

                                                                                                                                                                

## Tasks :page_with_curl:                                                                                                                                       

                                                                                                                                                                

* **0. What is my PID**                                                                                                                                         

  * [0-what-is-my-pid](./0-what-is-my-pid): Bash script that displays its own PID.                                                                              

                                                                                                                                                                

* **1. List your processes**                                                                                                                                    

  * [1-list_your_processes](./1-list_your_processes): Bash script that displays a list of currently running processes.                                          

  * Shows all processes for all users, including those not featuring a TTY.                                                                                     

  * Processes are displayed in a user-oriented hierarchy.                                                                                                       

                                                                                                                                                                

* **2. Show your Bash PID**                                                                                                                                     

  * [2-show_your_bash_pid](./2-show_your_bash_pid): Bash script that displays lines containing the `bash` keyword based on the script defined in `1-list_your_pr

ocesses`.                                                                                                                                                       

                                                                                                                                                                

* **3. Show your Bash PID made easy**                                                                                                                           

  * [3-show_your_bash_pid_made_easy](./3-show_your_bash_pid_made_easy): Bash script that displays the PID along with the process name of processes who name cont

ains the word `bash`.                                                                                                                                           

                                                                                                                                                                

* **4. To infinity and beyond**                                                                                                                                 

  * [4-to_infinity_and_beyond](./4-to_infinity_and_beyond): Bash script that displays `To infinity and beyond` indefinitely with a `sleep 2` in between each ite

ration.                                                                                                                                                         

                                                                                                                                                                

* **5. Don't stop me now!**                                                                                                                                     

  * [5-dont_stop_me_now](./5-dont_stop_me_now): Bash script that kills the [4-to_infinity_and_beyond](./4-to_infinity_and_beyond) process using `kill`.         

                                                                                                                                                                

* **6. Stop me if you can**                                                                                                                                     

  * [6-stop_me_if_you_can](./6-stop_me_if_you_can): Bash script that kills the [4-to_infinity_and_beyond](./4-to_infinity_and_beyond) process using `pkill`.    

                                                                                                                                                                

* **7. Highlander**                                                                                                                                             

  * [7-highlander](./7-highlander): Bash script that displays `To infinity and beyond` indefinitely with a `sleep 2` in between each iteration.                 

  * Displays `I am invincible!!!` upon receiving a `SIGTERM` signal.                                                                                            

                                                                                                                                                                

                                                                                                                                                                

* **8. Beheaded process**                                                                                                                                       

  * [8-beheaded_process](./8-beheaded_process): Bash script that kills the process [7-highlander](./7-highlander).                                              

                                                                                                                                                                

                                                                                                                                                                

![alt text](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/9/d8ecfe9109334898b9540ffd20cf64d1c06f0c09.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-

Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20220722%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220722T101619Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Si

gnature=8831f4931db87fcebcbad63936313cf1ea4a070d0d73bc8ba8531a85eb862046)                                                                                       

                                                                                                                                                                

"README.md" 75L, 4592C                           

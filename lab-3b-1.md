Lab 4 - Scripting Linux Server Functions Lab

In this lab, I learned how to write Bash scripts for creating file backups, using cron for scheduling, and exporting the files to the cloud.

<img width="634" height="509" alt="image" src="https://github.com/user-attachments/assets/5463ef16-c3ab-4b2c-8188-ffa7848c5bae" />
<img width="415" height="208" alt="image" src="https://github.com/user-attachments/assets/f676aa90-355b-4e18-a404-f1464404c3df" />

I tried to improve and modify the script while trying out the variables, arithmetic and a simple loop.

<img width="600" height="228" alt="image" src="https://github.com/user-attachments/assets/eaa1d9a1-4f93-4ba2-847a-9336c310474a" />
<img width="900" height="139" alt="image" src="https://github.com/user-attachments/assets/b61ae910-d0f2-43c3-9cf5-b9926f6953a0" />

I tried creating a backup script and moving the files located in /home/vboxuser/testscript to the backup directory. I learned about making the script accessible to other users by storing it in a common location.

<img width="900" height="516" alt="image" src="https://github.com/user-attachments/assets/d486f5b7-b501-4fe2-b53a-e37b915a0b3c" />
<img width="900" height="150" alt="image" src="https://github.com/user-attachments/assets/da38aacb-50a1-4229-9895-1566d1f73e54" />
<img width="809" height="789" alt="image" src="https://github.com/user-attachments/assets/093dc031-ea4c-4df7-85b4-17d1fe01ee11" />

I used cron to make the script run hourly. 
Cron runs automatically in the background on a fixed schedule without human interaction, using a stripped-down environment in which any interactive prompt, such as an SSH password or confirmation, will cause the job to stall or fail.

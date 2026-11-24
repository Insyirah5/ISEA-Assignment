Lab 3 - Amazon EC2 Web Services Lab

In this lab, I learned the steps to set up a cloud web service on Amazon Web Services (AWS) with EC2 instances.

<img width="900" height="468" alt="image" src="https://github.com/user-attachments/assets/2fac21ad-b566-4b5c-9f8f-da007d4558c0" />

<img width="900" height="414" alt="image" src="https://github.com/user-attachments/assets/412c1891-68a7-40de-aa2f-08327cf6462a" />
<img width="900" height="276" alt="image" src="https://github.com/user-attachments/assets/7a38988e-43d6-4a79-ab6c-a58806f88f58" />

I launched my first instance with the right configurations (port 22[SSH] and port 80[HTTP]) and installed Nginx in the terminal. Running an Ubuntu server in the cloud saves local CPU, RAM, and disk resources on my laptop. Launching an instance took less time with built-in networking and the ability to easily terminate resources when I'm done.



<img width="900" height="776" alt="image" src="https://github.com/user-attachments/assets/5a1218b0-4431-4836-863d-3a134b076e84" />

<img width="900" height="249" alt="image" src="https://github.com/user-attachments/assets/377b3b05-00a5-49e9-9baa-b2a45f24d65e" />

<img width="900" height="324" alt="image" src="https://github.com/user-attachments/assets/d112d67a-0a66-4113-be5b-b735dd5d5128" />

<img width="858" height="290" alt="image" src="https://github.com/user-attachments/assets/d164720f-b1ee-431e-b078-c22982c096e3" />

I managed to access the server using its public IP in a browser via HTTP.

<img width="900" height="274" alt="image" src="https://github.com/user-attachments/assets/d139a06e-4339-4a04-9704-9f050d7c366b" />
<img width="900" height="209" alt="image" src="https://github.com/user-attachments/assets/a30a2d82-15aa-441d-a7e0-71625b106fd6" />


<img width="1797" height="512" alt="image" src="https://github.com/user-attachments/assets/a7937c88-1153-49c8-a729-2194bcef696c" />

Lastly, I ensured the instances were shut down and terminated to prevent extra charges. I also set up a budget plan to alert me if the amount exceeded the limit. This is because leaving EC2 instances or attached EBS storage running continuously will consume AWS free-tier limits and accumulate ongoing hourly charges. 

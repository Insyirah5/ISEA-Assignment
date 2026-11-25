Lab 5 - Additional Server Service On vsftpd


<img width="900" height="368" alt="image" src="https://github.com/user-attachments/assets/996a5ac3-91fe-4171-abb0-68c2f7201543" />
<img width="900" height="324" alt="image" src="https://github.com/user-attachments/assets/ed8b192e-1fe4-452a-9d27-72409a351e54" />


I installed vsftpd using "apt install vsftpd -y", enabled it with "sudo systemctl enable --now vsftpd", and verified it was running with sudo systemctl status vsftpd.
The commands start with sudo because they require root privileges, as regular user accounts cannot modify system files, install software packages, or manage background services.

<img width="756" height="295" alt="image" src="https://github.com/user-attachments/assets/34ea4dd6-bcd8-4de8-81b7-ef5437a4e3f1" />
<img width="645" height="751" alt="image" src="https://github.com/user-attachments/assets/613efdab-3f2e-4a33-a156-747010b69fed" />

I configured /etc/vsftpd.conf to disable anonymous access, define a passive port range(40000-50000), and enabled firewall rules with ufw for ports 20, 21 and 40000:50000. Disabling anonymous access is required to prevent unauthorised access.


<img width="900" height="709" alt="image" src="https://github.com/user-attachments/assets/ff34653a-fa57-4646-9cac-db452da2ef90" />
<img width="900" height="162" alt="image" src="https://github.com/user-attachments/assets/2238aa60-b4a7-4b3d-8645-de2a73cea4c1" />

I logged in into ftp localhost as vboxuer, listed files and completed a file transfer.


# INTRODUCTION

File Inclusion is a web application vulnerability that occurs when an application allows a user-controlled input to determine which file is loaded or 
included by the server.If the application does not properly validate this input, an attacker may be able to access unintended files or, in some cases, 
execute malicious code.

# TYPES OF FILE INCLUSION
1. LFI – Local File Inclusion
   Allows an attacker to access files that already exist on the target server.
   Example: /etc/passwd
2. RFI – Remote File Inclusion
   Allows an attacker to include a file hosted on a remote server. This depends on the server-side language and
   its configuration.

#PRACTICAL STEPS OF FILE INCLUSION
1. Open browser to the host machine and type <kali linux ip>/DVWA. 
   e.g. http://192.168.190.135/DVWA/login.php
 <img width="1560" height="583" alt="image" src="https://github.com/user-attachments/assets/f6d72ff4-441c-4bcd-a95f-c88fa5dc3ba1" />
2. Select the DVWA security level
   . Low
   . Medium
   . High
3. Click on File inclusion
   <img width="1241" height="636" alt="image" src="https://github.com/user-attachments/assets/b598122b-2823-497e-a469-0c8374eac1fc" />
4. First find LFI ( Local File Inclusion) at low level
   <img width="1549" height="630" alt="image" src="https://github.com/user-attachments/assets/904f69c4-8592-4b7d-99d9-4d7508a80f7b" />
5. First find LFI ( Local File Inclusion) at Medium level
   <img width="1248" height="677" alt="image" src="https://github.com/user-attachments/assets/be2e4259-f4d7-489f-9dab-85268714db2f" />
6. First find LFI ( Local File Inclusion) at High level
  <img width="1517" height="634" alt="image" src="https://github.com/user-attachments/assets/41226c4d-88dd-4ad3-b742-c65430808da6" />







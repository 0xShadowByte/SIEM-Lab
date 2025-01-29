# SIEM Lab

## Objective
  
Learn how to generate security events on the Kali VM< set up an agent to forward data too the SIEM, and query and analyze the logs in the SIEM.

### Skills Learned

- Acquired hands-on experience in generating and analyzing security events using Nmap on Kali Linux
- Proficiency in deploying a Kali Linux VM
- Configure Elastic Agents for log collection and forwarding data to the SIEM for effective security event montioring
- Developed a custom dashboard in Elastic SIEM to visualize security events, demonstrating skills in data interpretation and pattern recognition
- Successfuly crreated and tested aleart rules for detecting specific security events, showing competency in proactive incident response and alert management 

### Tools Used

- VirtualBox VM
- Kali Linux VM
- Elastic SIEM

## Steps

*Ref 1: Setting up the agent to collect logs. Log in to Elastic SIEM instance and naviagte t the Integrations page by: clicking on the main menu bar at the top left, then selecting "Integrations" at the bottom*

![image](https://github.com/user-attachments/assets/1cbd8817-2823-401b-981b-8957f76ecd54)

*Ref 2: Copy the command line "linux tar" to install the agent on Kali VM*

![image](https://github.com/user-attachments/assets/0ac11ede-174f-4584-99a4-7a3f00b47b89)

*Ref 3: Installed agent on Kali VM and verifying if the agent is installed correctly by running: sudo systemctl status elastic-agent.service*

![image](https://github.com/user-attachments/assets/ba5c0c85-7050-41ac-b8ae-0b3edf04d4de)

*Ref 4: Using the nmap scan command to generate several security events*

![image](https://github.com/user-attachments/assets/70fc539c-4438-4c12-98db-b578b8a12205)

*Ref 5: Log of the security events*

![image](https://github.com/user-attachments/assets/560a7bb8-ff93-4a89-be63-2a4cee9da1d1)

*Ref 6: Vizualization of the security events as represented with a bar graph*

![image](https://github.com/user-attachments/assets/68ee9f12-86ec-4f9b-bf7e-be379d5c9955)

*Ref 7: Creating an alert by going to "Alerts" tab and click on "create search threshold rule"*

![image](https://github.com/user-attachments/assets/614633b5-b6f6-473b-880d-32004cd45693)

*Ref 8: An alert for nmap*

![image](https://github.com/user-attachments/assets/b3557f8a-b7b5-4477-b3c4-1096882489d6)

*Ref 9: Adding email alerts as an additional notification*

![image](https://github.com/user-attachments/assets/d5872275-8822-423b-bcbd-684d6fbe6503)


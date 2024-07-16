# Reverse Shell using Meterpreter and Metasploit on Kali Linux

## Project Overview

This project demonstrates the creation and execution of a reverse shell using Meterpreter and Metasploit on Kali Linux. The project is designed to showcase advanced penetration testing techniques and highlight the importance of robust cybersecurity measures.

## What is a Reverse Shell?

A reverse shell is a type of shell where the target machine initiates a connection back to the attacker machine, allowing the attacker to remotely control the target system. This technique is often used to bypass firewalls and network restrictions.

## Why Use Meterpreter and Metasploit?

Meterpreter, a powerful payload within the Metasploit Framework, offers a comprehensive suite of tools for post-exploitation activities. When combined with Metasploit, a widely used penetration testing framework, it provides a robust solution for executing and managing reverse shells.

## Project Steps

### 1. IP Discovery and Port Scanning

Identify the IP address of your attacking machine and use Nmap to scan the target machine’s open ports.

<img width="960" alt="Rev1" src="https://github.com/user-attachments/assets/e069d7fb-d24d-41b4-8424-6530181902be">

<img width="960" alt="rev2" src="https://github.com/user-attachments/assets/ad3dbe3f-f84b-43a0-8712-ba6f8951d86e">


### 2. Payload Generation

Generate a custom payload using the Social-Engineer Toolkit (SETOOLKIT) designed for the reverse shell connection.

<img width="960" alt="rev 3" src="https://github.com/user-attachments/assets/30235952-e5c4-48af-9996-045f822b5696">

<img width="960" alt="rev 4" src="https://github.com/user-attachments/assets/ecde6bc6-a16c-464a-abb0-8e954965ad66">




### 3. Configuration

Set up LHOST (attacker’s IP) and LPORT (listener port) in Metasploit.

![image](https://github.com/user-attachments/assets/61f430e4-ad61-490d-834b-98aefa56a09f)



### 4. Payload Delivery

Start the Apache service on Kali Linux to serve the payload and copy the generated payload to the Apache server for delivery to the target.
<img width="960" alt="image" src="https://github.com/user-attachments/assets/bd907e96-fa0c-4c45-a405-df043af60f7a">
<img width="960" alt="image" src="https://github.com/user-attachments/assets/6c8bec26-e153-4adf-b344-730ff6897b10">



### 5. Listener Setup

Initiate a listener on port 4444 using Metasploit. This listener will wait for the incoming connection from the target machine.
<img width="960" alt="image" src="https://github.com/user-attachments/assets/e6ef18b8-d037-467a-a5ae-516a5e997250">


### 6. Payload Execution

Deliver and execute the payload on the target Windows server. This can be done via social engineering techniques or exploiting vulnerabilities in the target system.
<img width="960" alt="image" src="https://github.com/user-attachments/assets/d8878a05-085a-4893-83a2-f53763dc217c">


### 7. Meterpreter Session

Once the payload is executed, a Meterpreter session starts in msfconsole, providing comprehensive control over the target machine.
<img width="960" alt="image" src="https://github.com/user-attachments/assets/d5a59ded-6d83-4d6c-8a51-fe30f2d5e690">


### 8. Windows Shell Access

With the Meterpreter session active, gain access to the Windows shell for further system manipulation and data extraction.
<img width="960" alt="image" src="https://github.com/user-attachments/assets/83a8fa5c-678f-4a74-b9b4-e0bf9a28001f">



## Key Takeaways

1. **Comprehensive Penetration Testing:** This project demonstrates the full lifecycle of a reverse shell attack, from reconnaissance to post-exploitation.
2. **Security Awareness:** Understanding these techniques highlights the importance of robust cybersecurity measures to defend against such attacks.
3. **Practical Skills:** The project enhances practical skills in using Metasploit, Meterpreter, and other essential tools for cybersecurity professionals.

## Conclusion

Successfully executing a reverse shell using Meterpreter and Metasploit on Kali Linux provides valuable insights into the methods used by cyber attackers. This project not only enhances your penetration testing skills but also underscores the critical need for strong defensive strategies in cybersecurity.

Whether you’re a budding cybersecurity professional or an experienced practitioner, mastering these techniques is essential for staying ahead in the ever-evolving world of cybersecurity.

## Disclaimer

This project is for educational purposes only. Unauthorized use of these techniques on systems without permission is illegal and unethical.

# Port-Scanning-and-Enumeration-on-Metasploit-
Identifying open ports, running services, and vulnerabilities on target system are key in making sure technology asset are secure. in this project I will demonstrate  using commands to identify open ports, detect running services, and gather critical information for security hardening.


# Objective
-Scan from root on Kali Linux
-Start Metasploit  framework console
-Start database
-Import scan to Metasploit 
-Check for XML file
-Create Workspace 
-Import XML file to workspace
-Analyze the hosts 
-Access workspace
-Scan from workspace

- 


Tools Used
-Kali Linux 
-VMware 



# Steps
-Scan from root mode nmap -sS -sV -O 192.168.*.* -oX  M1( -sS <conducting tcp scan>,-sV<detecting service and version>,-o<OS detection> oX <filing in xml format>
-Start Metasploit Metasploit framework console (msfconsole )
-Start database(msfdb init)
-Import scan to Metasploit console for Analysis (db_import)
-Check for XML file(ls)
-Access Workspace (Workspace <chosen name>)
-Import XML file to workspace (db_import M1>)
-Analyze the hosts (host)
-Crate workspace to analyze scan on database( workspace -a <chosen name>)
-Access workspace(workspace <name of workspace>)
-Scan from workspace (db_nmap -sS -sV -O 192.168.*.* )
 



# Key Findings
- Can be seen in the screenshot attached 
-<img width="542" height="218" alt="Scan from root on Kali Linux" src="https://github.com/user-attachments/assets/d2fb3878-4595-424d-ac6a-22d445d83534" />
<img width="539" height="237" alt="Start Metasploit framework console" src="https://github.com/user-attachments/assets/9d342af3-b93e-41fa-af72-03942d13eb34" />
<img width="539" height="304" alt="Start database" src="https://github.com/user-attachments/assets/14ac72fa-8f4b-4297-9a0b-e66f1fa5ed3b" />
<img width="535" height="122" alt="Import scan to Metasploit console for Analysis" src="https://github.com/user-attachments/assets/c8157bc9-9bbc-426c-bf47-d259b8d35ac5" />
<img width="541" height="130" alt="Analyze the host" src="https://github.com/user-attachments/assets/7ca7cb27-1d85-4da4-a710-92fef97887ff" />

<img width="530" height="249" alt="Scan from workspace on Metasploit" src="https://github.com/user-attachments/assets/a69bb16c-27e5-4792-bcfb-75e51ef5c9ff" />


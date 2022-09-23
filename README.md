![](assets/logo.png)

# Hooligan [ Work in Progress ]
> ## Completely powered by Nmap and nCrack, Hooligan is a simple and easy to use tool that can be used to automate the process of brute forcing services. Hooligan uses the ShodanIO engine to search for hosts and then uses Nmap to scan them for open ports. Once the ports are found, Hooligan uses nCrack to brute force the services. 

--
### Features
- [x] Brute force SSH, FTP, Telnet, HTTP, HTTPS, SMTP, RDP, VNC, MySQL, MSSQL, SMB, SNMP, VNC, RDP, MongoD - others coming soon.
- [x] Brute force multiple hosts at once.
- [x] Brute force multiple services at once.

--
### How to use
1. Clone the repository

    ```git clone https://github.com/darklulz/Hooligan.git```
2. Install the requirements

    ```pip install -r requirements.txt```
3. Run the script

    ```python hooligan.py```

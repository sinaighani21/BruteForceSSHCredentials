# BruteForceSSHCredentials


<h2>Description</h2>
Utilized Kali Linux tools, Metasploit, and Hydra to demonstrate how attackers can exploit vulnerabilities in weak SSH credentials through brute-force attacks. This project highlights the critical importance of addressing authentication vulnerabilities with robust password policies and secure configurations to protect servers from unauthorized access.
<br />


<h2>Tools and utilities used</h2>

- <b>Kali Linux</b> 
- <b>Metasploit</b>
- <b>Nmap</b>
- <b>Hydra</b>
<h2>Operating System Used </h2>

- <b>Kali Linux</b> 

<h2>Program walk-through:</h2>

<p align="center">
Using Nmap to scan the target and port: <br/>
<img src="https://i.imgur.com/YRykaZ9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Using Metasploit tool to exploit the vulnerability:  <br/>
<img src="https://i.imgur.com/Py3RxoZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
We can see that we have 1 session to gain access to the remote host: <br/>
<img src="https://i.imgur.com/Ug6TINm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
We successfully gained access to the remote host by typing the command "whoami":  <br/>
<img src="https://i.imgur.com/m5gYAj7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Using another tool called "Hydra" which is way faster then Nmap to crack passwords:  <br/>
<img src="https://i.imgur.com/rkn3hxW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<br />
<br />
</p>

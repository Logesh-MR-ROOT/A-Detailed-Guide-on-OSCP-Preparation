# A-Detailed-Guide-on-OSCP-Preparation
The Journey to Try Harder: 
                  For the past 2 years of my life I had one goal: Pass OSCP on my first try. This guide contains those resources and my advice to prepare for your adventure to take the PWK/OSCP!
                  
                  From the syllabus I will breakdown each section by providing you the resources I used to prepare for the course. Once I finish going through the syllabus, I will also be providing some extra resources that came in handy. You don’t need to use this guide in order; feel free to jump around as it suits you.

Getting Comfortable with Kali Linux
Essential Tools in Kali
Passive Reconnaissance
Active Reconnaissance
Vulnerability Scanning
Buffer Overflows
Working with Public Exploits
File Transfer
Privilege Escalation
Client-Side Attacks
Web Application Attacks
Password Attacks
Tunneling/Pivoting
Introduction to the Metasploit Framework
Antivirus Bypassing
               Kali Linux Revealed and Online Course: A good foundational course that helped me understand more about Kali Linux and it has a nice Linux Fundamentals section as well.

Book Link: https://kali.training/downloads/Kali-Linux-Revealed-1st-edition.pdf
Online Course Link: https://kali.training/lessons/introduction/
Bash Scripting: The bash Guide: A good guide to get you into the bash scripting

https://guide.bash.academy/
Linux Journey: A huge guide to learn about a variety of different things in Linux. All the lessons are free.

https://linuxjourney.com/
Explainshell: Awesome resource that parses a variety of man pages from Ubuntu Manage Repository. It breaks down the commands you are using, but it is best to refer to the man pages if you have any questions: .

https://www.explainshell.com/

 A quick intro on buffer overflow.

https://www.youtube.com/watch?v=1S0aBV-Waeo

What is Buffer Overflow?  (very clearly explained). After watching this video, you will get an idea on the concept behind buffer overflow. Also, will increase your urge on learning buffer overflow.

 Assembly language primer by Vivek Ramachandran. http://www.securitytube.net/groups?operation=view&groupId=5

Don’t get bored after seeing Assembly language. Just go through the first 2 videos in this video series. That is enough for understanding the memory layout.

 Buffer Overflow Megaprimer by Vivek Ramachandran. http://www.securitytube.net/groups?operation=view&groupId=4.

In-depth video of buffer overflow where its explained in a very detailed way.

Exploit Research Megaprimer by Vivek Ramachandran. http://www.securitytube.net/groups?operation=view&groupId=7

Some Valuable Resources           

These are some valuable resources which I found very useful in my OSCP Preparation. Many of them are now permanent reference resources even after I have cleared my OSCP.

Enumeration

http://www.0daysecurity.com/penetration-testing/enumeration.html

https://nmap.org/nsedoc/

https://www.youtube.com/watch?v=Hk-21p2m8YY

Shell Exploitation

http://pentestmonkey.net/cheat-sheet/shells/reverse-shell-cheat-sheet

http://www.lanmaster53.com/2011/05/7-linux-shells-using-built-in-tools/          

https://netsec.ws/?p=331

Windows Privilege Escalation

http://www.fuzzysecurity.com/tutorials/16.html

https://www.youtube.com/watch?v=kMG8IsCohHA

https://www.youtube.com/watch?v=PC_iMqiuIRQ

https://github.com/GDSSecurity/Windows-Exploit-Suggester     

Linux Privilege Escalation

https://blog.g0tmi1k.com/2011/08/basic-linux-privilege-escalation/

https://www.youtube.com/watch?v=dk2wsyFiosg

Privilege escalation recon scripts:

http://www.securitysift.com/download/linuxprivchecker.py

http://pentestmonkey.net/tools/audit/unix-privesc-check

http://www.abatchy.com/2017/02/oscp-like-vulnhub-vms.html

Exploiting a machine is a Systematic Process:

1)Find the open ports and services running on ports
2)Enumerate the services and the machine
3)Exploit the correct vulnerability and gain access
4)Do proper post exploitation enumeration
5)Privilege Escalation

The VMs in the above link will be like OSCP labs. You can start solving these VMs. For the vulnhub VMs, there are walkthroughs for each machine. You can try each machine first by yourself. Else read the walkthrough, understand it, and then try to implement the method again in the VMs.

Also, try this https://www.hackthebox.gr/


Try to pwn as many machines as you can. Again, TRY HAAAAARDER.

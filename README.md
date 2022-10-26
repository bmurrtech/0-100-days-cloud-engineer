![alt text](./images/0-100_Days_to_Cloud_Engineer.png)[^bannermaker]
[^bannermaker]: Created in [Banner Maker](https://banner.godori.dev/)
# Road to Cloud DevOps Engineer in 100 Days
Follow my daily journey of becoming a certified Cloud Engineer.

>He who aims at perfection<br>will probably miss the mark,<br>but he who aims at nothing,<br>is sure to hit it every time.
>
><br>--<cite>*Henry Wheeler Shaw, 1876*</cite>
<br>

**Table of Notable Achievements & Resources:**
1. [Linux Command Lines 1](#linux-command-lines-1)
1.

To-do:<br>
- [ ] Visual roadmap to Cloud Engineer (design in Canva)
- [ ] Create Chia + MadMax CLI command reference and list (in this repo)
- [ ] Create Online Resume
  - [ ] Step 1 - Markdown Resume (in this repo)
  - [ ] Step 2 - Create Resume using LaTeX[^tyalt1resume]
[^tyalt1resume]: Inspiration credit goes to [Tlyer Alterio](https://github.com/tyalt1/Resume)  

# Day :one:
- Started a course I thought would be everything I needed to become a DevOps Cloud Engineer
- First 5 hours into the course was all about the history of DevOps: agile, social coding, collaboration of developers and operations, etc.
- Listened to a cloud engineer livestream interview of an IT professional’s story of how he transitioned to cloud engineering.
  - He was already employed, so he just networked with the cloud manager
  - He learned what skills a cloud engineer needed
  - He has CCNA certification (networking skills that came in handy later)
  - He started AWS certification training
  - He later realized that he lacked basic Linux, Bash scripting, and Python skills
  - He started Python on codecademy, completed 50% and got hired as a jr. cloud engineer months later (he said codecademy it is worth every penny)

# Day :two:

- Ditched the first DevOps IBM course to deep-dive into research of what it really takes to be a cloud engineer
- Started searching job listings for the top required and most common skills mentioned
- Watched free content on YouTube to learn more about the primary DevOp skills required in real-life applications
- Chose a cloud service (AWS, Azure, Google) to pursue certification
- Paid for Coursera Plus (1yr)
- Searched for “Coursera Plus” and “Shareable Certificate” courses that checked all the boxes for key cloud engineering skills
- Found courses for Linux LFCA Certification, Google Cloud Associate certification prep, and Python
- Created roadmap and timeline (visualizing my goals)

# Day 3 :three:
- Completed required job skill research
- Completed creating learning roadmap by identifying key courses and optimizing for maximum learning to hours invested ratio
- Purchased [bmurr.tech](https://www.bmurr.tech) domain name with SSL and email mailbox
- Created custom domain email box
- Created a GitHub account to track and demonstrate my [0-100 days to Cloud Engineer progress](https://github.com/bmurrtech/0-100-days-cloud-engineer/blob/main/daily_journal.md)
- Made a stunning [About Me Github page](https://github.com/bmurrtech)
- Learned about and started utilizing [basic markdown syntax](https://www.markdownguide.org/cheat-sheet/)

## Learning About Linux History and Distributions
- Enrolled into Linux Fundamentals (Learn Quest) course through Coursera Plus subscription
- Started Week 1 of the course
- Learned the history of Linux.
- :bulb: **Fun fact**: Did you know that the creator of Linux, <mark>Linus Torvalds</mark>, was going to originally name it *Freax*? It is a combination or portmanteau of the two words “free” and “freak," and "x" being an allusion to Linux.
- Learning about Linux Distributions (i.e. Red Hat Enterprise Linux a.k.a. RHEL, 02-22-2000)
- RedHat is a subsidiary of IBM and targets server software for the commercial market
- CentOS is a redistribution with RedHat intellectual property (IP)
- Fedora Linux (11-06-2003) is more innovative (many releases) vs. RHEL philosophy which focuses on stability over innovation
- SUSE (soo-see) a German-based open-source tech company (09-2-1992); owned by Novell from 2003-2011
- Ubuntu is based on Debian (major category of distribution); free to download; ideal for desktop, server, core IoT devices, and robots (note about support: every two years a new update is released and long-term support is offered for 5 years total)
- Debian comes in stable, testing, and untested; similar to Ubuntu but Debian focuses on freedom (community-driven)

## Linux Command Lines 1
- Resource: [Linux CLI Intro Guide](https://linuxjournal.com/content/linux-command-line-interface-introduction-guide)
- 90% of the cloud is Linux based
- ssh is faster than interacting with a GUI
- the "bourne shell" is represented by the $ character to prompt the user for input
- Bourne **Sh**ell (sh) was originally developed by Stephen Bourne (not related to Jason Bourne!) while he was working at Bell Labs. 
- :bulb: **Fun fact**: Bash is an acronym for "**B**orne **A**gain **Sh**ell (B.A.SH). It was written as the free, open-source replacement of Bourne Shell. Because of the open-source nature of Bash, it has been adopted as the default shell on most Linux systems.

| Command | Description |
| ----------- | ----------- |
| pwd | returns the path of the current working directory (dir) |
| cd | change dir |
| cd .. | move one dir up |
| cd to | go straight to home folder |
| cd - | move to your prev dir |
| ls | lists contents of the dir |
| ls -r | will list all the files in the sub-directories as well |
| ls -a | will show the hidden files |
| ls -al | will list the files and dir with detailed info (ex. permissions, size, owner) |
| cat | list the contents of a file on the standard output |
| cat > filename | creates a new file |
| cat > filename1 filename2>filename3 | joins 2 files and stores the output of them in a new file |
| cp | copy files |
| mv | move or rename files |
| mkdir | create a new dir in the current dir |
| rm | remove file and directories |
| rm -r | remove dir and all files inside |
| clear | to clear the screen and start all over |
| history | will show a historical list of commands that were entered in the terminal session |

# Day :four:
- Completed Week 1 of Linux Fund. 100% score on week 1 module quiz :raised_hands: in 1-2 days. See the [Linux week 1 overview](https://d18ky98rnyall9.cloudfront.net/qRQY1L8KRNeUGNS_CnTXuQ_af9f7d4c30204287ac279be086d0c1f1_LinuxSpecializationCourse1Module1.pdf?Expires=1666656000&Signature=UJCINfl9vmCn1I33lc9u3J1zjFtZqeHU5Y33vUs2l35LE2GHXeaxIR~FvMFsgcCcfRKZ2~vk7v8g~wU6eskvWli0NK03Ghx85~Z3hstrd-tjtlCB58xGM0B0EY~nVB2gBYCiWyx5VmOw8JkKo8bPdArWbZOAMpE06p5BTXn4SqU_&Key-Pair-Id=APKAJLTNE6QMUY6HBC5A).
- Learned how to add folders to Git repository
  1. Go to the folder inside which you want to create another folder
  1. Click on New file
  1. On the text field for the file name, first write the folder name you want to create
  1. Then type /. This creates a folder
  1. You can add more folders similarly
  1. Finally, give the new file a name (for example, .gitkeep which is conventionally used to make Git track otherwise empty folders)
  1. Finally, click Commit new file.[^shadowfax]
[^shadowfax]: Credit: Shadowfax on [Stack Overflow](https://stackoverflow.com/questions/12258399/how-do-i-create-a-folder-in-a-github-repository)
- Learned more about Markdown (i.e. adding images, header linking, footers, lists/sublists)
- Watched an amazing video by Network Chuck about configuring Kubernetes (k3s) on a cluster of Raspberry Pi's with Rancher
- Witnessed the power of Nginx as a load balancer
- Learned that Linux largely depends upon the x86 architecture (making arm64, Raspberry Pi's, not ideal for full Kubernetes compatibility)
- Created IT resume and applied for IT specialist jobs focused in DevOps or Linux-based responsibilities
## Zima Board
The Raspberry-Pi-Killer :knife:
![alt text](./images/zimaboard1.jpg)
- Found out about [ZimaBoard](https://www.zimaboard.com/zimaboard/product), for home lab setup.
  1. The "World’s First Hackable Single Board Server" (kickstarter project)
  1. Quad-core 1.1-2.4GHz (Intel Celeron / Apollo Lake)
  1. 2G-8GB Dual Channel LPDDR4
  1. 16GB-32GB eMMC Storage
  1. 2x SATA 6.0 Gb/s
  1. 2x GbE LAN
  1. 1x PCIe 2.0 x4
  1. 1x Mini-DisplayPort 1.2 4k@60Hz
  1. TDP 6W
  1. Compatible OS Linux/Windows/OpenWrt/pfSense/Android/Libreelec
  1. Passive Cooling

# Day :five:
- Watched [Wolfgang Home Server Ansible Setup video](https://youtu.be/f5jNJDaztqk?t=1334) & was inspired to take on personal homelab/network project utilizing existing my server hardware from home
- Added [cybersecurity.md](https://github.com/bmurrtech/0-100-days-cloud-engineer/blob/main/home_network_cybersecurity.md) for personal home NAS security project
- Added [Ansible Data Dump .md](https://github.com/bmurrtech/0-100-days-cloud-engineer/blob/main/ansible-nas-doc.md) for future reference, for Ansible learning, & for Ansible automation home server project
- Discovered [The LaTeX Project](https://www.latex-project.org/) typesetting system & document builder
- Added a new repo for my LaTeX resume project
  - Want to utilize LaTeX to create my resume
  - Want to make repo able to create a [build of LaTeX document](https://github.com/bmurrtech/resume/edit/main/latex-doc-guide.md)
- Made a to-do list for major [home server project](https://github.com/bmurrtech/0-100-days-cloud-engineer/blob/main/home_network_cybersecurity.md) (I want to showcase Linux, containerization, & Ansible automation skills in the future)
- Signed up for [Python Morsels](https://www.pythonmorsels.com/billing/pricing/) - weekly guided Python practice exercises

## Week 2 of Linux
- [Linux Week 2 infograph overview](https://d18ky98rnyall9.cloudfront.net/06EkHSmFTT-hJB0phb0_Sw_1bc88a9afcaa46eb9afb6f9ae566daf1_LinuxSpecializationCourse1Module2.pdf?Expires=1666828800&Signature=aoPuF1waD9uQQUAOz2mXi4u2Ohb0-Sj6Qu-vji6gUpPJRdpHo3CkcdtEyk7vWUwXsQ9J3qtqZjdV1E2yRPdLZma0OSIALI5h0thXB9sSPt2bWBCK6BvBjI1u9OnuxPMzH0qIzgVirooIa4lmCIeQGoJ2jglClA9cVdqD9EvOR0E_&Key-Pair-Id=APKAJLTNE6QMUY6HBC5A)
### L1: Servers v Desktops
  - Severs: focuses on programs that proved shared resources/services
  - Desktop: focuses on programs that run in a Graphical User Interface (GUI)
  - Servers run prog in two primary ways: 1. as a background process (always running and listening to requests) 2. a process spawned by a parent program that listens for requests
- *Deamon* when a Linux services runs continually in the background, it is called a *deamon* and this processes often end in the letter "d" (ex. "mysqld")
- Major service types include:
  - file servers
  - print servers
  - web servers
  - database servers
  - mail servers
  - network resources servers (DHCP, logging, etc.)
- **Review L1**
  - A Linux *desktop* has programs designed around GUI interactive apps
  - A Linux *server* has programs designed around background services that share resources
  - Deamons often end with the letter "d" in their name
### L2 Web Servers
![alt_text](./images/kinsta-hosting-architecture.png)[^kinstawebserver]
[^kinstawebserver]: Photo Credits go to [Kinsta.com](https://kinsta.com/blog/nginx-vs-apache/)
  - Web servers listen on port 80 and 443 for incoming requests and assign the request to a process to return the response from the following providers:
  - *Apache*: free, open-source, cross-platform web server software released under Apache Lic. 2.0, 1995, compiled modules extend core funct. w/server-side languages (i.e. PHP, Python, Pearl, Tcl, etc.)
  - *NGINX*: free, open-source, cross-platform web server software released under FreeBSD license in 2004; owned by F5 Networks; modular, event-driven architecture can provide predictable performance under high loads (build time); *most popular web server* today with 432M servers running as of April 2021
  - *Lighttpd*: free, open-source, cross-platform web server software released under FreeBSD License in 2015; used in the past by several high-traffic websites (ex. YouTube); 33M servers running as of April 2021.
- **Review L2**
  - Web servers run in the background and serve HTTP and HTTPS requests
  - Apache is used by more sahred hosting providers
  - Nginx has taken much of the web server market because of performance
- Additional web server reading [Nginx v Apache](https://kinsta.com/blog/nginx-vs-apache/)
  - Web pages are "essentially HTML documents"
  - Therefore, you need a "serving" machine to "serve up" the visitor's browser the HTML document for viewing
  - :bulb: Fun-fact: Apache got its name either from 1. a Native American heritage or 2. from a pun on "a-patchy-server" :laughing: which ensued a series of software patches
  - Apache was made popular by its *dynamic module system*. A *module* is a feature that allows users to extend web server functionality. A list of modules can be found [here](https://httpd.apache.org/docs/2.4/mod/)
  - Nginx was created by a Russian dev, Igo Sysoev.
  - Nginx has a paid (Nginx Plus) and free version (BSD-type license).
  - Nginx was originally used as a *load-balancer* or *reverse proxy*
  - A *reverse proxy* "sits in front of a web server and receives all the requests before they reach the origin server and can enhance performance, reliability, and security of the web server."[^reverseproxy]
[^reverseproxy]: [Kinsta.com, *How To Set Up a Reverse Proxy..."](https://kinsta.com/blog/reverse-proxy/)
  - Because NGINX does not have a conf system like Apache, it is not commonly used for retail hosting providers.
### L3 - Database Servers
- Database Servers listen on the network for incoming requests (often SQL) and respond with data
- Relation Database Model is the dominant used in business applications
- SQL (Structured Query Language) [Official Documentation](https://dev.mysql.com/doc/mysql-getting-started/en/)
  - [Learn Basic SQL ft. Network Chuck](https://youtu.be/xiUTqnI6xk8)
  - Standard query language for DBMS
  - You can use SQL queries to retrieve data according to some criteria (i.e. retrieve name, phone, and email for customers in a specific zip code)
  - `SELECT name, phone, email FROM customers where zip_code = '01234'`
- NoSQL Database model is **document focused**
- *CRUD* stands for **C**reate **R**ead **U**pdate **D**elete
- **L3 Review**
  - Both Relational and NoSQL support CRUD operations
  - Relational is transactional focused
  - NoSQL is document focused

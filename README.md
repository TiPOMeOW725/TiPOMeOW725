ALEKSANDR PASHKOV  
Junior DevOps Engineer / Linux Administrator
--------------------------------------------------

Location: Belgrade, Serbia (open to remote)  
Email: gips8790@gmail.com  
GitHub: github.com/TiPOMeOW725  
LinkedIn: linkedin.com/in/aleksandr-pashkov-70116339a  

Availability: Immediate, full-time  

--------------------------------------------------
PROFESSIONAL SUMMARY
--------------------------------------------------

Linux and automation enthusiast focusing on DevOps. Hands-on experience with Linux server administration, Nginx web serving and reverse proxying, Docker and Docker Compose, shell scripting for monitoring and log analysis, and basic CI/CD using GitHub Actions.  

Built multiple small but complete projects: secure VPS setup with SSH and Fail2ban, static site hosting with Nginx and deployment scripts, a Docker-based traffic router using Nginx and FastAPI, log and performance analysis tools, and a Java Spring Boot financial tracker with documentation.  

Completed Red Hat Academy training in system administration and currently enhancing my skills with Terraform (basic EC2 provisioning) and Ansible (simple configuration playbooks).  
Looking for a Junior DevOps or Linux Administrator role where I can automate deployments, improve reliability, and grow within a technical team.

--------------------------------------------------
TECHNICAL SKILLS
--------------------------------------------------

DevOps and Automation  
- CI/CD: GitHub Actions (workflows triggered on push, build and deploy static sites)  
- Infrastructure as Code: Terraform (basic AWS EC2 and security group provisioning, remote state basics)  
- Configuration Management: Ansible (simple playbooks for package installation, user setup, and Nginx configuration in a home lab)

Containerization  
- Docker: writing Dockerfiles, building and running images, exposing services  
- Docker Compose: multi-container setups (for example Nginx reverse proxy + FastAPI application)

Linux and Networking  
- Distributions: Ubuntu, basic RHEL experience (Red Hat Academy labs)  
- Server administration: SSH configuration and keys, users and groups, file permissions, systemd basics  
- Security and hardening: Fail2ban for SSH, basic firewall setup (ufw, basic firewalld)  
- Web and networking: Nginx for static hosting and reverse proxy, HTTP, DNS, TCP/IP fundamentals

Scripting and Programming  
- Bash: automation scripts, log parsing, server performance monitoring tools  
- Python: small scripts and web application logic (FastAPI in Docker project)  
- Java and Web: Spring Boot, Spring Data JPA, Thymeleaf, H2 database (financial-tracker project)  
- SQL: simple queries and schema design for small applications

Version Control and Collaboration  
- Git and GitHub: branching, pull requests, GitHub Pages deployment  
- Technical writing: structured READMEs, DESIGN documents, usage instructions  
- Asynchronous communication: comfortable with written English communication and remote collaboration tools

Soft Skills  
- Technical writing and clear documentation  
- Asynchronous communication and self-organization  
- Cross-cultural adaptability (study and work experience across Russia, Czech Republic, and Serbia)  

--------------------------------------------------
PROJECTS AND HOME LAB EXPERIENCE
--------------------------------------------------

Simple Traffic Distribution System (Mini TDS) – Docker, Nginx, FastAPI  
Repository: Traffic-Router-Mini-TDS  
- Implemented a small HTTP traffic router using FastAPI behind Nginx.  
- Used Docker and Docker Compose to define and run a multi-container setup (FastAPI application container and Nginx reverse proxy container).  
- Configured Nginx as a reverse proxy, forwarding requests to the application container and passing client information through headers (for example X-Real-IP, X-Forwarded-For).  
- Implemented simple routing logic in the application based on IP prefix and User-Agent, to simulate geo-based and crawler-aware redirects.  
- Documented architecture, configuration, and testing scenarios in the README, including example curl commands and expected responses.

Static Website Deployment with Nginx and Deployment Scripts  
Repository: nginx-sokoban  
- Deployed a browser-based Sokoban game to a remote Linux VPS using Nginx as a web server.  
- Wrote a provisioning script to:  
  - Update packages, install Nginx and UFW  
  - Create a dedicated web root directory under /var/www  
  - Configure an Nginx server block for static file hosting  
  - Open HTTP traffic in the firewall  
- Implemented a local deployment script using rsync over SSH to synchronize updated static files to the server with minimal manual steps.  
- Demonstrates practical skills with Nginx configuration, firewall basics, and scripted deployments.

Remote Linux Server Setup and Hardening  
Repository: basic-remote-linux-server  
- Completed a roadmap.sh-style challenge to set up and secure a remote Linux server.  
- Configured SSH key-based authentication and disabled password login for better security.  
- Added SSH host aliases in ~/.ssh/config to simplify connecting to the server.  
- Installed and configured Fail2ban to protect the SSH service from brute-force attacks.  
- Shows understanding of basic VPS management, secure remote access, and entry-level hardening.

Nginx Access Log Analyzer Script  
Repository: nginx-log-analyzer  
- Wrote a Bash script to analyze Nginx access logs and compute useful statistics, including:  
  - Top client IPs by request count  
  - Most frequently requested URLs  
  - Distribution of HTTP status codes  
  - Most common user agents  
- Implemented parsing and aggregation using common Unix tools such as awk, sed, grep, sort, and uniq.  
- Demonstrates comfort with log formats, command-line tools, and building simple observability tools.

Server Performance Statistics Script  
Repository: server-performance-stats  
- Developed a Bash script to output key server health metrics on Linux:  
  - CPU usage  
  - Memory usage, including free and used memory with percentages  
  - Disk usage of key partitions  
  - Top processes by CPU and top processes by memory  
- Based on a DevOps challenge from roadmap.sh and uses standard tools (top, free, df, ps).  
- Shows understanding of basic server monitoring and how to present data in a readable format.

GitHub Actions Deployment Workflow for Static Site  
Repository: gh-deployment-workflow  
- Created a simple CI/CD workflow using GitHub Actions for a static website hosted on GitHub Pages.  
- Configured a workflow to run on each push to the main branch:  
  - Check out the repository  
  - Build static content if needed  
  - Deploy updated files to the gh-pages branch  
- Demonstrates understanding of basic CI/CD concepts and GitHub Actions syntax.

Financial Tracker Web Application  
Repository: financial-tracker  
- Implemented a small personal finance tracking application using Java, Spring Boot, Spring Data JPA, Thymeleaf, and H2 database.  
- Features include adding, editing, and deleting transactions, categorizing income and expenses, and viewing summary information.  
- Wrote additional documentation (for example DESIGN.md) and included database schema and data dump, demonstrating ability to describe architecture and data flow clearly.  
- Shows understanding of backend application structure and complements DevOps skills with basic knowledge of how applications are built.

Infrastructure as Code and Configuration Management Lab  
(Home lab work with Terraform and Ansible)  
- Used Terraform to provision a basic AWS EC2 instance and security group on the AWS free tier, practicing declarative infrastructure definition and state management basics.  
- Wrote simple Ansible playbooks to install packages, create users, and configure Nginx on a test server over SSH.  
- Focused on repeatable server setup and separating configuration from manual commands.  
- This work is part of ongoing self-study to strengthen Infrastructure as Code and configuration management skills.

--------------------------------------------------
EDUCATION AND TRAINING
--------------------------------------------------

Singidunum University, Belgrade, Serbia  
Bachelor of Software and Data Engineering, 2022 – present  
Status: Studies currently on academic leave to focus on professional development and full-time work.

Red Hat Academy – Professional Training  
- Red Hat System Administration I (RH124)  
- Red Hat System Administration II (RH134)  
- Introduction to OpenShift Applications (DO101)

Tomas Bata University, Zlín, Czech Republic  
Undergraduate IT Specialist coursework, 2021 – 2022  

--------------------------------------------------
LANGUAGES
--------------------------------------------------

Russian: Native  
English: B2 (Upper Intermediate) – comfortable with technical documentation and professional communication  
Serbian: Basic – actively learning and using in daily life

# Ansible

Infrastructure as code – IAC

### Why we use it?
To help speed up the process of the configuration management Ansible or orchestration. – Terraform
### How does it speed up the process?
By creating a script whether in YML file using ansible. YMAL = Another mark-up language
We can create a ansible VM/Controller and it will provision both the web and DB instances.
###What is ansible?
Automation tool for configuration management tool
- Simple
- Agentless
- IT automation tools – One of the most trending configuration management tools
- Connects using SSH – Any server in the world

### How does it fit into DevOps?
- Saves time
- Open source
- Makes configuration management predictable
- Cost effective
- It automates the process of configuration management 


Steps to install Ansible:

1) Create a directory called Ansible

2) Create a new file inside the Ansible directory called vagrantfile

3) Paste the code provided into the vagrantfile. This creates 3 DBs: Web, DB and AWS

4) Navigate to the Ansible directory and use the command vagrant up to initialise the machines.

5) Verify your machines are working by typing `vagrant status`

6) 
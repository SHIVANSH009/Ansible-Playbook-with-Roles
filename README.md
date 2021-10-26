# Ansible-Playbook-with-Roles
Using Ansible, a Configuration Management Tool, a playbook is created for setting up of Apache Tomcat and Apache Maven in the local. It uses ansible roles of apache tomcat and apache maven defined locally.

# How to run this code
1. Make sure Ansible is running on your system.
2. Clone this repository.
3. Open command line in the cloned folder, run ```sudo ansible-playbook setup.yml``` to start the setup.
4. Open ```localhost:8080``` in the browser to check apache tomcat status.
5. Run ```mvn -v``` in the command line to check apache maven version.

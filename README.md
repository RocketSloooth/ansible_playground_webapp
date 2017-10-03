# ansible_playground_webapp
Playground for Ansible Webapp deployment

Learning the ropes of Ansible with a simple scenario:
- Python-based web application
- 5 Cloud servers:
  - Ansible Control machine (control)
  - Nginx Load Balancer (lb01)
  - 2x App/Web Servers (app01/app02)
  - DB Server (db01)

The scenario is based on the Udemy course "Mastering Ansible" by Chris Lunsford.

As an exercise, I also decided to write Ansible playbooks while configuring a Lab
environment for a Jenkins course. These are stored under the playbooks/jenkins_lab
folder.

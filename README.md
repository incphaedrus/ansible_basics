Ansible Automation
 ➢ Types of Facts 
  a. Default Facts
  b. Custom Facts
 ➢ Custom Facts - Used to get the Extra Information about your managed 
Nodes.


 To get User Defined Facts.
 ➢ If Custom Facts are on Managed Nodes, then Custom Facts will be called 
default.
 ➢ Custom facts help to reduce the code lines in playbooks


 Ansible Automation
 ➢ Custom Facts help to build logic about environment specific 
configuration. User can execute config as per environment dev/non-prd/prd/stg.

 
 ➢ Steps to create Custom Facts 
a.Create /etc/ansible/facts.d on your managed nodes.
b. Inside the facts.d create one or more custom facts file with extension of .facts 
c. Output of the fact file should be JSON.
d. Fact file should have execution permission.

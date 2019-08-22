# Setting up Debian machines according to CIS Benchmark v1.0.0
This playbook will set up machines with Debian 9 installed using Ansible

# Requirements
To configure, you must have one machine with installed Ansible

To install Ansible, you must run `apt-get install ansible`

# Launch setup
To start the machine setup, you need to put all the files in one folder (preferably `/etc/ansible`) and execute the code `ansible-playbook playbook_debian.yml` (if the playbook name has not been changed).

All commands must be run with superuser privileges.

If you need to execute a specific section, execute the `ansible-playbook playbook_debian.yml --tags "SECTION_NUMBER"` where the SECTION_NUMBER indicates the desired section.

Section description:

**section_1**: General settings

**section_2**: Services settings

**section_3**: Network settings

**section_4**: Logging and Auditing settings

**section_5**: Access, Authentication and Authorization settings

**section_6**: System Maintenance settings 

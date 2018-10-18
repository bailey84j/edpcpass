---
- name: Create Additional DNS Records - Variables
  backout: Required
  requiredvars:
    # it is suggested that these be encrypted with ansible-vault:
    # ansible-vault edit group_vars/windows.yml
    ansible_ssh_port: 
    #ansible_winrm_kerberos_delegation: true
    ansible_winrm_transport: 
    ansible_connection: 
    ansible_ssh_user: ''
    ansible_ssh_pass: ''
    ipv4address: "10.174.47.100"
    ipmask: "24"
    zone:
    name:
  optionalvars:
  
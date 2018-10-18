---
- name: Configure Symantec Endpoint Protection - Variables
  backout: Not Required
  requiredvars:
    # it is suggested that these be encrypted with ansible-vault:
    # ansible-vault edit group_vars/windows.yml
    ansible_ssh_port: 
    #ansible_winrm_kerberos_delegation: true
    ansible_winrm_transport: 
    ansible_connection: 
    ansible_ssh_user: ''
    ansible_ssh_pass: ''
    domain: ''
  optionalvars:
  
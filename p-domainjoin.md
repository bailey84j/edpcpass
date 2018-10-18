---
- name: Join to Domain
  backout: Not Required
  requiredvars:
    # it is suggested that these be encrypted with ansible-vault:
    # ansible-vault edit group_vars/windows.yml
    ansible_ssh_port: 5985
    ansible_winrm_kerberos_delegation: 
    ansible_winrm_transport: 
    ansible_connection: 
    ansible_ssh_user: ''
    ansible_ssh_pass: ''
    domain_user: ''
    domain_password: ''
    domain: ''



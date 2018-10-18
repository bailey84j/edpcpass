---
- name: get and set network attributes - variables
  backout: Not Required
  requiredvars:
    vCenter_FQDN: ""
    vCenter_UserName: ""
    vCenter_Password: ""
    vm_username: ""
    vm_password: ""
    vm_name: ""
    vm_folder: ""
    json_name: ""
    datacenter: ""
    southip: ""
    southgate: ""
    southmask: ""
    domainsuffix: ""
    dnsservers: ""
  optionalvars:
    mgtip: ""
    mgtgate: ""
    mgtmask: ""
    dmzip: ""
    dmzgate: ""
    dmzmask: ""
    bkpip: ""
    bkpgate: ""
    bkpmask: ""

sep
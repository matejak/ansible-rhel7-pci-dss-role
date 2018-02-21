PCI-DSS v3 Control Baseline for Red Hat Enterprise Linux 7
=========

Ansible remediation role for profile pci-dss  
Profile Title:  PCI-DSS v3 Control Baseline for Red Hat Enterprise Linux 7  
Profile Description:  
This is a *draft* profile for PCI-DSS v3.  
  
Benchmark ID:  RHEL-7  
Benchmark Version:  0.1.38  
  
XCCDF Version:  1.1  
  
This file was generated by OpenSCAP 1.2.16 using:  
	$ oscap xccdf generate fix --profile pci-dss --template urn:xccdf:fix:script:ansible sds.xml   
  
This script is generated from an OpenSCAP profile without preliminary evaluation.  
It attempts to fix every selected rule, even if the system is already compliant.  
  
How to apply this remediation role:  
$ ansible-playbook -i "192.168.1.155," playbook.yml  
$ ansible-playbook -i inventory.ini playbook.yml

Requirements
------------

N/A

Role Variables
--------------

TODO

Dependencies
------------

N/A

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: username.rolename }

License
-------

BSD-3-Clause

Author Information
------------------

This Ansible remediation role has been generated from the body of security policies developed by the SCAP Security Guide project. Please see https://github.com/OpenSCAP/scap-security-guide/blob/master/Contributors.md for an updated list of authors and contributors.

Purpose:

Deploy two virtual routers (R20 and R21) running quagga in in a programatic manner, establish EBGP, and exchage EBGP routes.

Assumptions:
Host OS CentOS-7
Hypervisor KVM
Guest VMs OS CentOS-7
Hypervisor networks 192.168.64.0/24 and 100.100.100.0/24 doesn't exist in the hypervisor.

Package Structure:
Directory exercise contains the following:
  Directory r20 which contains the kickstart fille for router 20.
  Directory r21 which contains the kickstart fille for router 21.
  Python scrypt deply_lab which execute the job.
  
Instructions:
Modify the iso_location variable to poing to the OS (CentOS-7-x86_64-DVD-1503-01.iso)
Run python deploy_lab.py as root.







  
  




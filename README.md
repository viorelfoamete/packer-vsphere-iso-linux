# Packer templates for Linux using vSphere-ISO provider

This repository contains **HashiCorp Packer** templates to deploy **Linux** distros in **VMware vSphere**. 

# Content: #

**CentOS7 Base**

* CentOS7/centos7-vsphere.json --> CentOS7 Packer JSON file
* CentOS7/ks.cfg --> CentOS7 Kickstart file

Tested with **VMware ESX 6.7** | User: root | Password: server

**CentOS7 Base with Cloud-Init**

* CentOS7-CloudInit/centos7-vsphere.json --> CentOS7 Packer JSON file
* CentOS7-CloudInit/ks.cfg --> CentOS7 Kickstart file

Tested with **VMware ESX 6.7** | User: root | Password: server

**CentOS7 Base with Cloud-Init**

* CentOS7-CloudInit/centos7-vsphere.json --> CentOS7 Packer JSON file
* CentOS7-CloudInit/ks.cfg --> CentOS7 Kickstart file

Tested with **VMware ESX 6.7** | User: root | Password: server

**Ubuntu 18.04**

* Ubuntu-18.04/ubuntu18.json --> Ubuntu 18.04 Packer Template JSON file
* Ubuntu-18.04/variables.json --> Ubuntu 18.04 Packer Variables JSON file
* Ubuntu-18.04/preseed.cfg --> Ubuntu Preseeding file

Tested with **VMware ESX 6.7** | User: kopicloud | Password: kopicloud


# Requeriments: #

* Builder for VMware vSphere (**vsphere-iso**) --> https://www.packer.io/docs/builders/vmware/vsphere-iso

* Packer --> https://www.packer.io


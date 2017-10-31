# Cloud

    This repository is intended to explore some cloud related technologies and terms like

    1. KVM
    2. QEMU
    3. Libvirt
    4. QCOW2
    5. Vagrant
    6. Cloud-Init
    7. Ansible
    8. Docker

# Raw Section

## 1. KVM

Kernel-based virtual machine is a virtualization infrastructure for the Linux Kernel that turns it into a hypervisor:

A hypervisor or virtual machine monitor is a computer software, firmware or hardware that creates and runs virtual machines. The hypervisor presents the guest operating system with a virtual operating platform and manages the execution of host operating systems.

There aret two types of hypervisors. 

* Native or Bare Metal Hypervisors

These hypervisors run directly on the hosts hardware to control the hardware and to manage guest operating systems. For this reason they are sometimes called bare metal hypervisors

eg. Xen , Oracle VM Server for Sparc, Oracle VM Server for x86, Microsoft Hyper-V

* Hosted Hypervisors

These hypervisors run on a conventional operating system just as other computer programs do. A guest operating system runs as a process on the host. Type-2 hypervisors abstract guest operating systems from the host operating systems.

eg. VMware, Workstation, VirtualBox, QEMU 

!(hypervisors.png)
Th

You can run instances of variety of operating systems that will share the virtualized hardware resources. This is in contrast with the operating system-level virtualization ( like containers ) where all instances share same kernel



## 2. QEMU

QEMU ( short for Quick Emulator ) is a free and opensource hypervisor  that performs hardware virtualization. 
 



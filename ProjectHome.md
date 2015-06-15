# Virtual Machine Manager for Webmin #

Allows control of virtual machines from Xen or KVM (in fact, every virtualization control based on libvirt) from the Webmin interface. Here are the feature list provided by this tool :

  * Pause / Resume VM
  * Start a VM
  * Shutdown a VM
  * Destroy a VM
  * Take control of the VM through an embedded VNC Viewer client right from Webmin.

_This fork is based on the original work done by Clement Veret from which a few modifications were done to modify VNC port assignments when trying to connect to a VM._
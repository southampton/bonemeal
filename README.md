# bonemeal

__A lightweight text mode post-install system for RHEL6 and RHEL7 integrating with Puppet and VMware__

### What is bonemeal?

Red Hat's kickstart system is great at automating installations of RHEL, but its support for post-installation tasks is relativley poor. bonemeal was written to provide a menu-driven or automatic post-installation system which runs after the kickstart process has finished and the system has rebooted.

Bonemeal is the sister project of [diorite](https://github.com/southampton/diorite) - the server component for bonemeal.

bonemeal is targetted at:

- "In the field" deployment of RHEL workstations/desktops to allow deployment staff to set up and customise RHEL and join the systems to Puppet and other systems.
- Fully automatic end-to-end deployment of RHEL6+7 servers including joining Puppet (Without autosign) using VMware UUID checking.

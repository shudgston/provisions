# Jenkins

Sets up Vagrant VM provisioned with a basic Jenkins CI server installation.


## Installation

You can copy this directory to wherever you like to keep Vagrant files.

With Ansible and Vagrant already installed, run the following commands from this directory.

```
# Install a prepackaged jenkins role
ansible-galaxy install geerlingguy.jenkins
ansible-galaxy install geerlingguy.git
vagrant up
```

When everything completes, you should have a running jenkins server accessible from localhost:8080.

# Jenkins

Sets up Vagrant VM provisioned with a basic Jenkins CI server installation.  See the top-level README file for installation prerequisites.


## Installation

You can treat this directory like any old directory that contains a Vagrantfile.  You may want to completely copy this directory to another location on your file system to avoid polluting the repository.

With Ansible and Vagrant already installed, run the following commands from this directory.

```
# Install a prepackaged jenkins role
ansible-galaxy install geerlingguy.jenkins
ansible-galaxy install geerlingguy.git
vagrant up
```

When everything completes, you should have a running jenkins server accessible from localhost:8080.

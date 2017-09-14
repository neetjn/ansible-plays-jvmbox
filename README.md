# ansible-plays-john
Ansible playbook to install personal tools required for my workspace, and setup my environment.

This project is a sub-project of the [JVM Development Environment](https://github.com/neetVeritas/jvm-development-environment). The Ansible plays described here will be applied to the Vagrant environment being built.

These plays will only suffice for the the Ubuntu based distributions.

### Software List

* file-roller
* nano
* curl
* httpie
* gedit
* skypeforlinux
* hipchat-4
* vscode
* aws-cli
* docker
* docker-compose
* pylint
* node.js lts stable (n)
* coffeescript
* webpack (version 2.2.0)

### Prerequisites
* ansible 2

### Use

Clone the repository,
```sh
git clone https://github.com/neetVeritas/ansible-plays-john.git
```
Run the playbook,
```sh
ansible-playbook playbook.yml
```

---
Copyright (c) 2017 John Nolette, Oro Team Licensed under the MIT license.

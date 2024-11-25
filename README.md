# PNK_Ansible_Automation

## Table of Contents

1. [Overview](#overview)
2. [Ansible Installation](#ansible-installation)
3. [Usage](#usage)

## <a name="overview"> Overview </a>

This is a small side project to help automate the creation and configuration of a portable network kit (PNK) server. These
are ansible playbooks designed to excuted on a Raspberry Pi 4 or 5. These playbooks install and configure most of what
comprises the PNK Server. As of right now there is a playbook that sets up web server using apache hosting a wordpress
site. As well as a playbook dedicated to make installing the unifi controller for the Raspberry Pi easier.

### What is ansible?

Ansible is an automation tool used to maintain multiple computers/servers. By giving a control node a playbook and an inventory file
of all the machines you want it to automate, it can take over simple tasks such as installations.

Read more <a href="https://www.ansible.com/how-ansible-works/">here.</a>

## <a name="ansible-installaiton"> Ansible Installation </a>

### Mac

You will need to install the HomeBrew package manager.

```bash
#Copy and paste the install command into your terminal
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

For more info click <a href="https://brew.sh">here.</a>

### Windows

As of right now you cannot use a windows machine as a control node. (Read more <a href="https://docs.ansible.com/ansible/latest/os_guide/intro_windows.html#windows-control-node">here.</a>)
Therefor you will need to install the Windows Subsystem for Linux (WSL).

Official install guide <a href="https://learn.microsoft.com/en-us/windows/wsl/install">here.</a>

### Linux

For your specific distribution of linux, please refer to the <a href="https://docs.ansible.com/ansible/latest/installation_guide/index.html">ansible documentation.</a>

## <a name="usage"> Usage </a>

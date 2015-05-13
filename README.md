## Ansible User-Add

This is a useful Ansible playbook for creating user accounts across multiple servers in bulk.

### Requirements

You will need to have the following installed to use this script

```
ansible
sshpass library
python passlib library
```

### First Time Fun

To setup for the first time simply browse to a new folder on your Ansible 
enabled workstation / server and execute the following commands:

Pull the latest master branch with the following command(s):

```bash
git clone https://github.com/Dave-Melia/ansible-playbook-useradd.git
```

## user-add.yml

Allows you to add users to multiple servers in bulk.


### Usage

Edit 'hosts' file and enter the hostnames we are configuring under the `[all]`
directive.

Once done execute the following command:

```bash
./adduser
```

The playbook will then prompt you for the various bits of data you require to create the account(s). 



> "How does a project get to be a year behind schedule? One day at a time." - Fred Brooks

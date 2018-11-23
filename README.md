### Deploy LAMP Stack and Wordpress with Ansible playbook on Ubuntu 16.04 (AWS Cloud)

##### 1). Update and Upgrade distro following command: (Select : Packages Maintainer Version )
```
$ sudo apt update -y && sudo apt dist-upgrade -y
```
##### 2). Install ansible playbook.
```
$ sudo apt install ansible -y
```
##### 3). Go to in your ansible path and Git clone lampW stack to your Servers.
```
$ cd /etc/ansible/ && sudo git clone https://github.com/sysadmin-clicknext/training-buu-ansible-deployment.git
```



### Deploy LAMP Stack and Wordpress with Ansible playbook on Ubuntu 16.04 (AWS Cloud)

##### 1). Update and Upgrade distro following command: (Select : Packages Maintainer Version )
```
$ sudo apt update -y && sudo apt dist-upgrade -y
```
##### 2). Install ansible playbook.
```
$ sudo apt install ansible -y
```
##### 3). Go to $HOME path and Git clone lampW stack to your Servers.
```
$ cd $Home && sudo git clone https://github.com/sysadmin-clicknext/training-buu-ansible-deployment.git
```
##### Example ansible playbook deployment (Must on ansible Directory path)
```
$ ansible-playbook -i hosts playbook.yml
```
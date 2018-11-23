### Deploy LAMP Stack and Wordpress with Ansible playbook on Ubuntu 16.04 (AWS Cloud)

##### 1). Update and Upgrade distro following command: (Select : Packages Maintainer Version )
```
$ sudo apt update -y && sudo apt dist-upgrade -y
```
##### 2). Install ansible playbook.
```
$ sudo apt install ansible -y
```
##### 3). Go to your $HOME and Git clone lampW stack to your Servers.
```
$ cd $Home && sudo git clone https://github.com/sysadmin-clicknext/training-buu-ansible-deployment.git
```
##### Example ansible playbook deployment (Must on ansible Directory path)
```
$ ansible-playbook -i hosts playbook.yml
```

### Variables

###### Define your name of DomainName
```
your_domain_names: ""
```
###### Define your name of DomainName
```
your_domain_names: ""
```
###### Define name of database.
```
wordpress_db_name: ""
```
###### Define username of database.
```
wordpress_user_name: ""
```
###### Define password of database.
```
wordpress_user_pass: ""
```
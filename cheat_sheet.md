Unix Command Cheat Sheet

In order to use

`whoami` - print out the userid (username)  
http://linux.about.com/library/cmd/blcmdl1_whoami.htm

`pwd` - print the name of the current directory or path  
http://linux.about.com/library/cmd/blcmdl1_pwd.htm

`ehco` - display a line of text in the shell  
http://linux.about.com/library/cmd/blcmdl1_echo.htm

`useradd` - create new user (or update default user info)  
http://linux.about.com/od/commands/l/blcmdl8_useradd.htm  
    
  - EG, `useradd -h /home/deploy -m -b /bin/bash deploy`  

`passwd` - change a user's password  
http://linux.about.com/od/commands/l/blcmdl5_passwd.htm

`usermod` - modify a user  
http://linux.about.com/od/commands/l/blcmdl8_usermod.htm
 
  - EG, `usermod -aG sudo deploy`

`chown` - edit directory or file owner/group  
http://linux.about.com/od/commands/l/blcmdl1_chown.htm  

  - EG, `chown -R deploy:root /var/www`

`chmod` - edit directory or file permissions  
http://linux.about.com/od/commands/l/blcmdl1_chmod.htm  
  
  - EG, `chmod -R 755 /var/www`

`groups` - print the groups a user is in  
http://linux.about.com/library/cmd/blcmdl1_groups.htm

`apt-get update` - update software packages available for install  
http://linux.die.net/man/8/apt-get

`apt-get install` - installs package on operating system  
http://linux.die.net/man/8/apt-get  
  
  - EG, `apt-get install nginx`
  
  - EG, `apt-get install git`
  

`cd` - change directory  
http://www.linfo.org/cd.html

`ls` or `ls -als` - list file and directory contents  
http://linux.about.com/od/commands/l/blcmdl1_ls.htm

`ps aux` - list all operating system processes  

`grep <example_word>` - match and print results for `<example_word>`  

`ps aux | grep nginx` - list processes and find nginx processes  
  
  - EG, `ps aux | grep node`  
  
  - EG, `ps aux | grep forever`  

`service <service> <command>` - executes Linux init scripts  
  
  - EG, `service nginx start`  
  
  - EG, `service nginx restart`  
  
  - EG, `service nginx stop`  

`mkdir` - create directory

`git clone` - clone code repository (code project)

`nano` - shell text editor

`add-apt-repository` - add a custom `apt-get` repository

`node` - command line access to Nodejs

`npm` - node package manager, like `apt-get` but for Nodejs code

<br>
<br>
<br>

`forever` - command access to Forever Javascript Daemon process manager
  
  - `forever --help` - list forever help info
  
  - `forever start server.js` - start the `server.js` process and keep it going
  
  - `forever list` - list all the processes that forever is managing
  
  - `forever stopall` - stop all forever processes

<br>
<br>
<br>

`vagrant` - command access to the vagrant program

  - `vagrant help` - list vagrant help info 
  
  - `vagrant init` - creates Vagrantfile in current directory if one does not exist
  
  - `vagrant up` - Creates and configures guest machines according to Vagrantfile
  
  - `vagrant status` - Tells you state of Vagrant machines
  
  - `vagrant provision` - Runs any configured provisioners against the running Vagrant managed machine
  
  - `vagrant ssh` - SSH into a running Vagrant machine (as `vagrant` user)
  
  - `vagrant reload` - Equivalent of running `vagrant halt` and `vagrant up`
  
  - `vagrant suspend` - Suspends Vagrant machine. Saves machine state to Hard Drive
  
  - `vagrant resume` - Resumes suspend Vagrant machine
  
  - `vagrant halt` - Shuts down Vagrant machine
  
  - `vagrant destroy` - Destroys all Vagrant machine resources
  
  


Installation
===
* Copy ec2ssh to e.g. /usr/local/bin/
* Copy ec2hosts to e.g. /etc/bash_completion.d/
* Run ec2ssh --repopulate (which creates a cache of ec2 worker instancess under ~/.ec2ssh for use by tab completion)

Usage
==============
* ec2ssh o-prod-log --- where o is oregon (s for sydney), and prod-log is worker name
* `ec2ssh o-prod-log -p` which means your konsole will think it's running ssh, instead of ec2ssh
#Todo
* Script to tell us server is shutdown

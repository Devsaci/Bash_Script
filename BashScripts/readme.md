# commandes

$ vagrant up scriptbox
sacid@Gen□ve MINGW64 /d/Bash_Script (main)
$ vagrant up scriptbox
Bringing machine 'scriptbox' up with 'virtualbox' provider...
==> scriptbox: Box 'geerlingguy/centos7' could not be found. Attempting to find and install...
    scriptbox: Box Provider: virtualbox
    scriptbox: Box Version: >= 0
==> scriptbox: Loading metadata for box 'geerlingguy/centos7'
    scriptbox: URL: <https://vagrantcloud.com/api/v2/vagrant/geerlingguy/centos7>  
==> scriptbox: Adding box 'geerlingguy/centos7' (v1.2.27) for provider: virtualbox
    scriptbox: Downloading: <https://vagrantcloud.com/geerlingguy/boxes/centos7/versions/1.2.27/providers/virtualbox/unknown/vagrant.box>
    scriptbox:
==> scriptbox: Successfully added box 'geerlingguy/centos7' (v1.2.27) for 'virtualbox'!
==> scriptbox: Importing base box 'geerlingguy/centos7'...
==> scriptbox: Matching MAC address for NAT networking...
==> scriptbox: Checking if box 'geerlingguy/centos7' version '1.2.27' is up to date...
==> scriptbox: Setting the name of the VM: Bash_Script_scriptbox_1714987343796_43613
==> scriptbox: Clearing any previously set network interfaces...
==> scriptbox: Preparing network interfaces based on configuration...
    scriptbox: Adapter 1: nat
    scriptbox: Adapter 2: hostonly
==> scriptbox: Forwarding ports...
    scriptbox: 22 (guest) => 2222 (host) (adapter 1)
==> scriptbox: Running 'pre-boot' VM customizations...
==> scriptbox: Booting VM...
==> scriptbox: Waiting for machine to boot. This may take a few minutes...
    scriptbox: SSH address: 127.0.0.1:2222
    scriptbox: SSH username: vagrant
    scriptbox: SSH auth method: private key
    scriptbox: Warning: Connection reset. Retrying...
    scriptbox: Warning: Connection aborted. Retrying...
    scriptbox: Warning: Remote connection disconnect. Retrying...
    scriptbox: Warning: Connection aborted. Retrying...
    scriptbox: Warning: Connection reset. Retrying...
    scriptbox: Warning: Connection aborted. Retrying...
    scriptbox: Warning: Connection reset. Retrying...
    scriptbox:
    scriptbox: Vagrant insecure key detected. Vagrant will automatically replace
    scriptbox: this with a newly generated keypair for better security.
    scriptbox:
    scriptbox: Inserting generated public key within guest...
    scriptbox: Removing insecure key from the guest if it's present...
    scriptbox: Key inserted! Disconnecting and reconnecting using new SSH key...
==> scriptbox: Machine booted and ready!
==> scriptbox: Checking for guest additions in VM...
    scriptbox: The guest additions on this VM do not match the installed version
of
    scriptbox: VirtualBox! In most cases this is fine, but in rare cases it can  
    scriptbox: prevent things such as shared folders from working properly. If you see
    scriptbox: shared folder errors, please make sure the guest additions within
the
    scriptbox: virtual machine match the version of VirtualBox you have installed on
    scriptbox: your host and reload your VM.
    scriptbox:
    scriptbox: Guest Additions Version: 6.1.32
    scriptbox: VirtualBox Version: 7.0
==> scriptbox: Setting hostname...
==> scriptbox: Configuring and enabling network interfaces...
==> scriptbox: Mounting shared folders...
    scriptbox: /vagrant => D:/Bash_Script

## $ vagrant ssh scriptbox

[vagrant@scriptbox ~]$

## [vagrant@scriptbox ~]$ sudo -i

[root@scriptbox ~]#

## vi /etc/hostname

[root@scriptbox ~]#

## [root@scriptbox ~]# hostname scriptbos

## [root@scriptbox ~]# logout

There are stopped jobs.

## [root@scriptbox ~]#logout

Vim: Caught deadly signal HUP
Vim: preserving files...
Vim: Finished.

## [vagrant@scriptbox ~]$ logout

## $vagrant ssh scriptbox

Last login: Mon May  6 18:43:40 2024 from 10.0.2.2

[vagrant@scriptbos ~]$

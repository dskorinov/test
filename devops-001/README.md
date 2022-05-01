# MENU
# Public ssh key
this is my key [ssh-rsa ... user@user] rsa algorithm with 4096 length: just to be sure.

# virtual box settings

# shared fs:
 cat /etc/fstab 
#<file system> <mount point>   <type>  <options>       <dump>  <pass>
/dev/disk/by-id/dm-uuid-LVM-AE7RYeuw0Q7LkV2gyKQ7j0m0DkJSoKcQCcxbye3tiZiFVOMJLZ0TWkTV8pAlzCPw / ext4 defaults 0 1
/dev/disk/by-uuid/b203107c-ef21-4d62-8b9c-f58700d334f6 /boot ext4 defaults 0 1
/swap.img	none	swap	sw	0	0
shareddisk	/var/shareddisk	vboxsf	defaults	0	0	

ls -la /var/ | grep sha

# docker
systemctl status docker
● docker.service - Docker Application Container Engine
     Loaded: loaded (/lib/systemd/system/docker.service; enabled; vendor preset: enabled)
     Active: active (running) since Sat 2022-04-30 06:03:45 UTC; 1h 9min ago


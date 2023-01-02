# Virtualizing_RHEL

Need to download/learn more about VirtualBox: https://www.virtualbox.org/
VIM Cheat Sheet: https://devhints.io/vim

Reference:
<Command>

Commands:
Network Card:
<nmcli>
<vi /etc/sysconfig/network-scripts/ifcfg-enp0s3>
</sbin/reboot now> - Need to have elevated privileges to run this command
Register System:
<subscription-manager register --username <username> --password <password> --auto-attach>
Adding user to sudoers file:
<usermod -aG wheel <username>>
Update System:
<sudo dnf update> 
Note use -y at the end of the command to automatically have packages updated without asking for permission.
Install Additional Packages:
<sudo dnf install kernel-devel make gcc -y>

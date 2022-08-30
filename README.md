# Ansible

Ansible scripts to automate setup and maintenance of hardware in my homelab

adduser.yaml - add a user to host(s) and to sudo group on host(s)
ansible.cfg - my ansible config file
config-rsyslog.yaml - modify hosts rsyslog configuration to set log file to central loghost
fixresolver/ - 
hosts - sample ansible host file
host.yaml
installapps.yaml - apt update, apt upgrade, apt autoremove, and install additional packages on host
install-docker.yaml - install docker on a host
new-install.yaml - 
setup-k3s-host.yaml - apt update, apt upgrade, apt autoremove, add cgroup config, config rsyslog, and reboot the host
update.yaml - apt update, apt upgrade, apt autoremove, install common packages on all hosts, VMs and lxc containers

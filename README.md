yum install net-tools lsof nano wget nano lsof net-tools wget unzip iptables-services bzip2  -y


wget https://dl.fedoraproject.org/pub/epel/epel-release-latest-7.noarch.rpm -O /root/epel-release-latest-7.noarch.rpm


yum localinstall /root/epel-release-latest-7.noarch.rpm -y


yum install iptables-services -y


yum groupinstall development tools -y 


bash <(curl -Ls  https://raw.githubusercontent.com/sangscript/ovpnscript/main/radius_openvpn_installer.sh)



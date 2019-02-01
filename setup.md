root
setup-alpine
us
us
#setup new password
# setup localhost name
enter
enter
enter
sda
sys
y
reboot


apk add nano
nano /etc/ssh/sshd_config
/etc/init.d/sshd restart



nano /etc/network/interfaces
/etc/init.d/sshd restart
/etc/init.d/networking restart



nano /etc/apk/repositories


apk update
apk add docker

rc-update add docker boot
service docker start


apk add py-pip
pip install docker-compose

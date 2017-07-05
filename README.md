# ntp

cp /etc/ntp.conf /etc/ntp.conf.1
> /etc/ntp.conf
nano /etc/ntp.conf
service ntpd status
service ntpd restart
chkconfig --list |grep ntp
chkconfig ntpd on
grep synchronized /var/log/messages
ntpdc -c sysinfo |egrep 'reference ID|reference time'
ntpdate -q server_ip
ntpdate -u server_ip

https://www.ntp-servers.net/

http://www.server-world.info/en/note?os=CentOS_6&p=ntp

http://blog.smart-admin.ru/nastrojka-ntp-servera-v-centos.html

http://www.cyberciti.biz/faq/rhel-fedora-centos-configure-ntp-client-server/

https://access.redhat.com/documentation/en-US/Red_Hat_Enterprise_Linux/6/html/Deployment_Guide/s1-Understanding_the_ntpd_Configuration_File.html

http://belgorod.lug.ru/wiki/index.php/NTPD_-_%D0%BD%D0%B0%D1%81%D1%82%D1%80%D0%BE%D0%B9%D0%BA%D0%B0_%D1%81%D0%B5%D1%80%D0%B2%D0%B5%D1%80%D0%B0_%D0%B2%D1%80%D0%B5%D0%BC%D0%B5%D0%BD%D0%B8

https://bbs.archlinux.org/viewtopic.php?id=110718

http://www.tldp.org/LDP/sag/html/basic-ntp-config.html


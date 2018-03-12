# Nagios Configuration Files

apt-get -y install mc apache2 php5 nagios3 sendemail gcalcli libio-socket-ssl-perl libnet-ssleay-perl

nano /etc/nagios3/conf.d/myhosts.cfg 

/etc/init.d/apache2 restart 
/etc/init.d/nagios3 restart

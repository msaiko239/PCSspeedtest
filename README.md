# PCSspeedtest
PCS Technologies Speed Test

# Prerequsites
Apache2 or other web server
PHP 7.X 

# Installation
sudo apt-get update
sudo apt install apache2
sudo apt-get install php libapache2-mod-php php-mcrypt php-mysql
(most liekly you do not need all the php modules but I like to down them all)
git clone https://github.com/msaiko239/PCSspeedtest.git
cd PCSspeedtest/pcsspeedtest
cp -r * /var/www/html/

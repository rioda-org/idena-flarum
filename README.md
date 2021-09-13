# idena-flarum
Flarum forum + Idena Authentication

# Aditional setup things
sudo apt update
sudo apt install php7.4-gmp
sudo apt install php-bcmath
nano /etc/php/7.4/cli/php.ini
(uncoment #extension=gmp)
sudo systemctl restart apache2.service

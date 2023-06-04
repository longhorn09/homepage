# Website for normstorm.com
source code for normstorm.com

to install apache

```
sudo apt install apache2
```

clone into 

```
/var/www/html
```

Firewall configuration
```
sudo ufw allow 'Apache'
sudo ufw status
sudo ufw allow http
```

Enable ufw
```
sudo ufw enable
```

Set home page directory in Apache
```
sudo vim /etc/apache2/sites-enabled/000-default.conf
```

Restart Apache
```
sudo systemctl restart apache2
```

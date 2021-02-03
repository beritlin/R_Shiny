# Web server setting

**Enviroment**

Ubuntu: 16.04.2

Apache: 2.4

PHP: 7.3



**Install Apache2**

```bash
sudo apt install apache2
```

```bash
sudo ufw app info "Apache Full"
```



**Install PHP**

```bash
sudo apt purge libapache2-mod-php7.3 libapache2-mod-php
sudo apt install libapache2-mod-php7.3 libapache2-mod-php
```

```bash
sudo a2enmod php7.3
sudo /etc/init.d/apache2 restart
```

 


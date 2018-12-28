# Item Catalog Deployment
Deployment of the item catalog CRUD application on a linux server as part of the Udacity Fullstack Developer Nanodegree.

**IP address**
18.194.244.0

**SSH port**
2200

**Complete URL to the hosted web application**
http://18.194.244.0/

**Software installed and configuration changes made**
- `apache2`, `mod_wsgi`, `postgresql`
- application home: `/var/www/item-catalog/vagrant/catalog`
- `wsgi` file: `/var/www/item-catalog/vagrant/catalog/item-catalog.wsgi`
- `apache2`virtual hosts file: `/etc/apache2/sites-available/item-catalog.conf`
- Python3 virtual environment location: `/var/www/item-catalog/vagrant/catalog/env`

**A list of any third-party resources to complete this project**
- Linux server hosted by amazon lightsail
- The SSH key for login with username `grader` provided during project sumbission
- Tutorial followed: http://flask.pocoo.org/docs/1.0/deploying/mod_wsgi/


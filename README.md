Linux Server Configuration
======

IP: 63.35.23.91

SSH port: 2200

URL: http://ubuntusecurity.tk

Packages installed
======

apache2 libapache2-mod-wsgi git python python-flask python-sqlalchemy python-requests 
python-oauth2client

Changes made to VM
======

ufw configured to allow only 2200,80,123

added port 2200 to /etc/ssh/sshd_config

configured apache following: http://flask.pocoo.org/docs/0.12/deploying/mod_wsgi/

grant www-data user ownership of catalog.db file

Third Party Resources
======

http://flask.pocoo.org/docs/0.12/deploying/mod_wsgi/

Blueprint Template, you can find info here: https://github.com/DevSam96/Catalog-App


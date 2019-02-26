Linux Server Configuration
======

IP: 63.35.23.91
SSH port: 22 (unable to set a different port for SSH, see: 
https://knowledge.udacity.com/?nanodegree=5d0abf4a-496f-11e8-b517-e31790f491a9&page=1&query=ssh%20port&sort=RELEVANCE 
)
URL: http://ubuntusecurity.tk/

Packages installed
======

apache2 libapache2-mod-wsgi git python python-flask python-sqlalchemy python-requests 
python-oauth2client

Changes made to VM
======

ufw configured to allow only 22,2200,80,123
added port 2200 to /etc/ssh/sshd_config
configured apache following: http://flask.pocoo.org/docs/0.12/deploying/mod_wsgi/
grant www-data user ownership of catalog.db file

Third Party Resources
======

http://flask.pocoo.org/docs/0.12/deploying/mod_wsgi/

Blueprint Template, you can find info here: https://github.com/DevSam96/Catalog-App


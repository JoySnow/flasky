Preparations:
=============

1. Install a DB demaon and grant proper access to related user.
2. Pip install packages according to requirements. (fix by yourself)
3. Try to run $ python manager.py runserver
   or $ python manager.py test
4. Set up some other needed part and fix errors.
5. Until it can start normally.


How to set up email usage?
==========================

1. create a bash file, eg, env.sh.
2. $ cat env.sh
> export FLASKY_ADMIN=xxx@163.com
export MAIL_SERVER=smtp.163.com
export MAIL_PORT=25
export MAIL_USE_TLS=True
export MAIL_USERNAME=xxx@163.com
export MAIL_PASSWORD=<Shou Quan Ma>

3. $ chmod +x env.sh
4. $ source ./env.sh

So, these variables are accessable to config.py.

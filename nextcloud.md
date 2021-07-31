NEXTCLOUD DIRECTORIES
===============

<b> APPS downloaded/enabled from within the app are stored here...</B>
``` YAML
/usr/local/www/nextcloud/apps 
```
- If you are experiencing permission issues, go to the NextCloud shell and type...
<em>This grants recursive ownership of that directory and everything below it.</em>
``` YAML
cd /usr/local/www/nextcloud/apps

chown -R www:www *
```
This grants the directory and everything below it recursively.

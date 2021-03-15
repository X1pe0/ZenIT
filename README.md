# ZenIT
Verify employee security awareness.  ZenIT is a way to send fake spam emails to employees and track their security awareness.

## Apache Config
PHP, Python and postfix packages are needed.
```
<VirtualHost *:80>
   DocumentRoot /var/www/html/web
   Servername example.com
   <Directory /var/www>
   AllowOverride All
   </Directory>
   CustomLog /var/log/apache2/access.log combined
   ErrorLog /var/log/apache2/error.log
</VirtualHost>
```

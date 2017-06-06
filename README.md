# Drupal BIBBOX application


## Docker Images Used

- drupal:8.3.2-apache
- mariadb:latest
- busybox:latest
 
 
## Database information

- MYSQL root password: thispasswordisneverusedeveninsidethecontainer
- Database: drupal
- User: drupal
- Password: drupal4bibbox
- Host: drupal-db


## Mounted Volumes

- /var/lib/mysql
- /var/www/html/modules
- /var/www/html/profiles
- /var/www/html/themes

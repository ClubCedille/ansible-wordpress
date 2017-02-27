# Ansible-wordpress

## Description
Projet ansible pour installer wordpress de manière autonome.

## Variables

Les variables qui demandes à être à changer sont dans *group_vars/all*

Ce qui doit être changé:
```
 server_hostname: 'foo.com'
 apache_server_admin: admin@foo.com	

 wordpress_mysql_user_passwd: 'Foo123'
 wp_mysql_db: 'wordpress'
 wp_mysql_user: 'wordpress'

 mysql_root_password: 'Foo123'

```



Здесь находится конфигурация dovecot.
Всё настроено так, что логины и пароли беруться из файла /etc/dovecot/dovecot-users
Его нужно создать и внести пользователей. 
Так же необходимо не забыть сделать перезагрузку служб после этого. 

sudo service postfix restart
sudo service dovecot restart

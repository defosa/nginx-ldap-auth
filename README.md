# nginx-ldap-auth
Настройка  LDAP

- default.conf - пример конфигурации nginx
- nginx-ldap-auth-daemon.py не большой http сервер.
- nginx-ldap-auth-daemon.service - демон 

 /etc/systemd/system/nginx-ldap-auth-daemon.service
 
systemctl daemon-reload
systemctl enable nginx-ldap-auth-daemon.service
systemctl start nginx-ldap-auth-daemon

systemctl status nginx-ldap-auth-daemon

-------------

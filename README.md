# nginx-ssl-experiment
Learning nginx and ssl

In /etc/nginx run: 
```
openssl req -x509 -nodes -days 365 -newkey rsa:2048 -keyout www.example.com.key -out www.example.com.crt
```

This will create fake certificates so nginx will start up over ssl. Your browser will be salty.

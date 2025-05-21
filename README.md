## Lancer un container docker 
```bash
sudo docker run -dit --name Tecmint-web -p 8080:80 -v /home/niko/php/MVC/:/usr/local/apache2/htdocs/ httpd:2.4
```

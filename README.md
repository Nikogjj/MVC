- Lancer un container docker 
```bash
sudo docker run -dit --name le_nom_de_votre_container -p 8080:80 -v /path/to/your/directory/:/usr/local/apache2/htdocs/ httpd:2.4
```
en modifiant le --name et le -v 
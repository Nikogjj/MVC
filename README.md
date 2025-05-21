- Lancer un container docker 
```bash
sudo docker run -dit --name le_nom_de_votre_container -p 8080:80 -v /path/to/your/directory/:/usr/local/apache2/htdocs/ httpd:2.4
```
en modifiant le --name et le -v 

En faisant cette commande je lance un container docker en reliant 
le PORT 8080 de ma machine hôte au PORT 80 de mon container docker.

Je "monte" le dossier /path/to/your/directory/ de ma machine hôte à l'emplacement /usr/local/apache2/htdocs/ de mon container (emplacement des fichiers web apache)

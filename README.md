Écoute par défaut au port 8051

Pour construire l'image docker : 
* sudo docker build -t docker-flask project/. 
        -->nommer une image "docker-flask" à partir du fichier Dockerfile dans project
* sudo docker run -p 8051:8051 docker-flask
        -->rouler l'instance de docker au port 8051

NE PAS tuer un processus docker avec KILL. plutôt, faire :
* docker ps
* docker kill 03u3r903r09u3r09u
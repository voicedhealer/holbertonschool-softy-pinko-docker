# Utiliser la dernière version d'Ubuntu comme image de base
FROM ubuntu:latest

# Mettre à jour APT
RUN apt-get update

# Mettre à niveau les logiciels installés
RUN apt-get upgrade -y

# Installer Python3, pip3 et Flask
RUN apt-get install -y python3 python3-pip

# Résoudre le problème d'environnement externe si nécessaire
RUN rm /usr/lib/python*/EXTERNALLY-MANAGED

# Installer Flask avec pip3
RUN pip3 install flask

# Définir le répertoire de travail
WORKDIR /app

# Copier le fichier Python dans l'image
COPY ./api.py /app/api.py

# Commande par défaut pour lancer l'application Flask
CMD python3 api.py

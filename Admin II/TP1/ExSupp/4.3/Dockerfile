# Utilise l'image officielle Python comme image de base.
FROM python:3.9-slim

# Définit le répertoire de travail dans le conteneur
WORKDIR /app

# Copie le script Python dans le répertoire de travail.
COPY show_time.py .


# Définit la commande par défaut pour exécuter le script Python à la création du conteneur.
CMD ["python", "./show_time.py"]
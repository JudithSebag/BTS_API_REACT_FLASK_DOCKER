# backend/Dockerfile
FROM python:3.11-alpine

# Définir le dossier de travail
WORKDIR /app

# Copier les fichiers du backend
COPY . .

# Installer les dépendances
RUN pip install --no-cache-dir -r requirements.txt

# Exposer le port Flask
EXPOSE 5000

# Lancer Flask
CMD ["flask", "run", "--host=0.0.0.0", "--port=5000"]

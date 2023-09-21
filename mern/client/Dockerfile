# utilise l'image node:alpine officiel comme image de base
FROM node:alpine
# Définit le répertoire de travail de l'application dans le conteneur
WORKDIR /app
# Copie le fichier package.json dans le répertoire de travail
COPY package.json .
# Installe les dépendances de l'application
RUN npm install
# Copie le reste du code source de l'application dans le répertoire de travail
COPY . .
# Lance l'application
CMD ["npm", "start"]
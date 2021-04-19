# CV21Rest

## WebApp (Le Client)

### Développement sur l'api clevercloud

- Un client React est fourni dans le dossier `webapp`
- Placez vous à la racine du dossier `webapp`
- Éxecutez votre environnement de développement avec `npm run start`, le serveur par défaut npm tournera sous le port `3000`
- Par défaut l'adresse de l'api est réglé sur `http://app-cd3c9847-3e85-4c3f-83bb-1f1fae7844d2.cleverapps.io/`

### Développement sur l'api en local
- Éxecutez votre environnement de développement avec `npm run local`, le serveur par défaut npm tournera sous le port `3000`
- Par défaut l'adresse de l'api est réglé sur `localhost:8080` (adresse à modifier dans package.json)

### Deploiement en production

- Placez vous à la racine du dossier `webapp`
- `npm build` pour construire l'application pour la production
- Un dossier `build` sura alors créé contenant l'application construite, le point d'entrée de l'application est le fichier index.html
- L'application peut maintenant fonctionner avec un serveur applicatif configuré

# CV21Rest

## WebApp (Le Client)

- Vous devez utiliser la version 14 ou supérieur de nodejs

```bash
# Avec Ubuntu
curl -fsSL https://deb.nodesource.com/setup_14.x | sudo -E bash -
sudo apt-get install -y nodejs
```

### Développement sur l'api clevercloud

- Placez vous à la racine du projet
- `npm install` pour installer les modules
- Éxecutez votre environnement de développement avec `npm run start`, le serveur par défaut npm tournera sous le port `3000`
- Par défaut l'adresse de l'api est réglé sur `http://app-cd3c9847-3e85-4c3f-83bb-1f1fae7844d2.cleverapps.io/`

### Développement sur l'api en local
- Éxecutez votre environnement de développement avec `npm run local`, le serveur par défaut npm tournera sous le port `3000`
- Par défaut l'adresse de l'api est réglé sur `localhost:8080` (adresse à modifier dans package.json)

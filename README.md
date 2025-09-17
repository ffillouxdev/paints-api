Ce projet met à disposition une API REST simulée pour accéder à des informations sur des peintures, en utilisant [my-json-server](https://my-json-server.typicode.com/ffillouxdev/paints-api/paintings/).

## Fonctionnalités

- Accès à une collection de peintures via une API RESTful.
- Chaque peinture contient : titre, artiste, année, thème, et une URL d'image.

## Structure des données

```json
{
    "paintings": [
        {
            "id": ...,
            "paint_title": "...",
            "artist": "...",
            "year": ...,
            "theme": "...",
            "url": "..."
        }
        // ...
    ]
}
```

## Utilisation

1. Forkez ce dépôt et ajoutez votre fichier `db.json` avec la structure ci-dessus.
2. Rendez-vous sur [my-json-server.typicode.com](https://my-json-server.typicode.com/) et utilisez l'URL de votre dépôt pour accéder à l'API.

Exemple d'endpoint :
```
GET https://my-json-server.typicode.com/<votre-utilisateur>/<votre-repo>/paintings
```

## Ressources

- [my-json-server Documentation](https://github.com/typicode/json-server)
- [Typicode/json-server](https://github.com/typicode/json-server)


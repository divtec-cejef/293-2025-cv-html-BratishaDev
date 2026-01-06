## A) normalize.css doit être en local (pas de CDN)
- Vous utilisez Normalize via un CDN
- Veuillez le télécharger et le placer dans `./css/normalize.css`
- Puis corriger le `<head>` :

```
<link rel="stylesheet" href="./css/normalize.css">
<link rel="stylesheet" href="./css/main.css">
```

## B) Dosser CSS : utilisez `css/` (pas `/CSS`)
- À mettre en minuscule
- et corriger le chemin du fichier CSS

```
<link rel="stylesheet" href="./css/main.css">
```

## C) Favicons : à la racine et avec `./`
- Vos favicons sont dans `images/`
- Veuillez mettre les favicons à la racine du projet et les référencer avec `./`
- Exemple :
```
<link rel="icon" href="./favicon.ico">
<link rel="icon" type="image/png" sizes="32x32" href="./favicon-32x32.png">
<link rel="icon" type="image/png" sizes="16x16" href="./favicon-16x16.png">
<link rel="manifest" href="./site.webmanifest">
```

## D) Photo du header : ouvrir dans un nouvel onglet + sécurité
- Veuillez ajouter `target="_blank"` et `rel="noopener noreferrer"` sur le lien de la photo
- Exemple :
```
<a class="logo" href="./img/chat-officiel.png" target="_blank" rel="noopener noreferrer">
  <img src="./img/chat-officiel.png" alt="Photo de Andrii Dimov">
</a>
```

## E) Corriger le HTML invalide (balise `<h2>` mal fermée)
- Vous avez une balise non fermée :
  - `<h2>Ma formation</h2`
- Veuillez corriger en :
```
<h2>Ma formation</h2>
```

## Autres
- Évitez les espaces dans les noms de fichiers (ex: `Chat officiel.png`) : renommez par exemple `chat-officiel.png`



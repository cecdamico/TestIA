# TestIA — Site vitrine

Site vitrine statique et basique (HTML, CSS, JavaScript), sans dépendance ni build.

## Structure

- `index.html` : page unique (accueil, services, à propos, références, contact)
- `style.css` : styles, responsive
- `script.js` : menu mobile et année du footer

## Lancer en local

Ouvrir `index.html` dans un navigateur, ou :

```bash
python3 -m http.server 8000
```

puis aller sur http://localhost:8000.

## Mise en ligne

Compatible GitHub Pages : Settings → Pages → Branch `main` / dossier racine.

## À personnaliser

Le nom « Maison Lumen », les textes, l'adresse, l'email et les références sont des contenus d'exemple à remplacer.
Le formulaire de contact n'envoie rien : il faut le brancher à un service (Formspree, Netlify Forms, backend…).

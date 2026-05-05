# Mini API Chat (HTML)

Application web simple en **un seul fichier** (`index.html`) pour discuter avec un modèle via API.

## 1) Visualiser l'application

### Option A — Ouvrir directement le fichier
1. Télécharge `index.html`.
2. Double-clique dessus pour l’ouvrir dans ton navigateur.

### Option B — Lancer un serveur local (recommandé)
```bash
python3 -m http.server 8000
```
Puis ouvre : `http://localhost:8000/index.html`

## 2) Télécharger l'application
Tu as deux possibilités :

### Télécharger seulement l'app
- Récupère le fichier `index.html` (c’est toute l’application).

### Télécharger depuis ce dossier vers ton disque
```bash
cp index.html ~/Downloads/mini-api-chat.html
```

### Télécharger tout le projet en ZIP
```bash
zip -r mini-api-chat.zip index.html README.md
```

## 3) Utilisation
1. Saisis ta clé API en haut à droite.
2. Clique sur **+ Nouveau chat** à gauche.
3. Écris ton message puis clique sur **Envoyer** (ou `Ctrl/Cmd + Enter`).
4. Utilise le bouton **Copier** sous chaque message si besoin.

## Remarque importante
La clé API est stockée dans le navigateur (`localStorage`) sur ta machine.


## 4) Publier sur GitHub Pages (lien cliquable)
1. Pousse ce dépôt sur GitHub.
2. Va dans **Settings → Pages**.
3. Dans **Build and deployment**, choisis **Source: GitHub Actions**.
4. Le workflow `.github/workflows/pages.yml` déploiera automatiquement `index.html`.

Lien public attendu :
- `https://<ton-user>.github.io/<ton-repo>/`

Exemple :
- `https://moncompte.github.io/mini-api-chat/`

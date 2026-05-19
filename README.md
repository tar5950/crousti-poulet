# Crousti Poulet — Site de commande

Site vitrine et commande en ligne. Un seul fichier `index.html`, images
intégrées, zéro dépendance hors Google Fonts. Hébergeable tel quel sur
GitHub Pages.

Site réalisé par TK Digital.

## Contenu du dossier

- `index.html` — le site complet (HTML, CSS, JS)
- `bowl-signature.jpg` — bowl signature
- `bowl-epice.jpg` — bowl épicé / fire
- `supp-poulet.jpg` — supplément poulet croustillant
- `desserts.jpg` — dessert
- `hero.jpg` — visuel d'accueil PROVISOIRE (à remplacer par le hero KOKO)

Les fiches sans image affichent un placeholder propre tant que le
fichier n'est pas présent. Le site ne casse jamais.

## Mettre en ligne sur GitHub Pages

Le dépôt et l'URL doivent t'appartenir. Étapes, environ deux minutes.

### 1. Créer le dépôt distant (sur ton compte)

1. Va sur https://github.com et connecte-toi.
2. Bouton vert "New" (ou https://github.com/new).
3. Repository name : `crousti-poulet`
4. Laisse en "Public".
5. Ne coche rien d'autre. Bouton "Create repository".

### 2. Pousser le code

Dans un terminal, depuis ce dossier décompressé :

```
git remote add origin https://github.com/TON_PSEUDO/crousti-poulet.git
git branch -M main
git push -u origin main
```

Remplace `TON_PSEUDO` par ton identifiant GitHub. Le premier commit est
déjà fait, tu n'as qu'à pousser.

### 3. Activer GitHub Pages

1. Sur la page du dépôt : onglet "Settings".
2. Menu de gauche : "Pages".
3. Source : "Deploy from a branch".
4. Branch : `main`, dossier `/ (root)`. Bouton "Save".
5. Patiente une à deux minutes. L'URL publique s'affiche en haut de la
   page Pages, du type `https://TON_PSEUDO.github.io/crousti-poulet/`.

## Personnalisation

Tout se règle dans `index.html` :

- Bloc `CONFIG` en haut du script : numéro WhatsApp, téléphone,
  adresse, ville, lien Google Maps, réseaux.
- Bloc `MENU` : remplace les noms, descriptions et prix entre crochets
  par le vrai menu Crousti Poulet.

## Vidéo du hero (optionnel)

Pour activer la vidéo de fond : dépose un fichier nommé exactement
`hero-video.mp4` à la racine du dépôt, à côté de `index.html`. Format
MP4, court, muet, idéalement sous 4 Mo. Tant qu'il est absent, le
visuel `hero.jpg` et le fond béton néon s'affichent.

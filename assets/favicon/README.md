# Votre favicon

C'est la petite icône de l'onglet du navigateur. Vous la créerez au bloc 01.

**Un fichier, une ligne.** Nommez-le `favicon.svg` et rangez-le ici.

## Le fabriquer

Un SVG suffit : tous les navigateurs actuels l'acceptent, il reste net à toutes
les tailles, et il pèse quelques centaines d'octets. Pas de générateur, pas de
jeu de fichiers à produire.

Créez `favicon.svg` dans ce dossier, collez ceci, puis changez les initiales et
la couleur :

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100">
  <rect width="100" height="100" rx="20" fill="#1c5fd6" />
  <text x="50" y="70" text-anchor="middle" font-family="sans-serif"
        font-size="56" font-weight="700" fill="#ffffff">CR</text>
</svg>
```

## Le déclarer

Une ligne dans le `<head>` de chacune de vos pages :

```html
<link rel="icon" href="assets/favicon/favicon.svg" type="image/svg+xml">
```

> **Le piège.** Un favicon qui « ne change pas » est presque toujours du cache
> du navigateur, pas une erreur de code. Vérifiez en navigation privée avant de
> chercher plus loin.

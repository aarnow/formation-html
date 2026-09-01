# Formation HTML

Projet d'exemple réalisé dans le cadre de l'apprentissage du HTML.
Réalisation d'un petit site web permettant la découverte et la mise en pratique
du HTML, des notions et des outils qui s'y rattachent.

## Ce qui vous est fourni

| Fichier           | Description                                                                                                                                     |
| ----------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| `css/base.css`    | La feuille de style du projet. **Vous n'avez pas à l'écrire ni à la modifier.** Elle est là pour rendre votre travail lisible et plus agréable. |
| `css/style.css`   | Volontairement vide.                                                                                                                            |
| `assets/img/`     | Pour stocker vos images.                                                                                                                        |
| `assets/favicon/` | Pour stocker votre favicon.                                                                                                                     |
| `.vscode/`        | Les réglages de l'éditeur et les extensions conseillées. VS Code vous proposera de les installer à l'ouverture du dossier.                      |
| `.prettierignore` | Empêche l'éditeur de reformater votre HTML à votre place.                                                                                       |

Les dossiers `assets/img/` et `assets/favicon/` contiennent chacun un
`README.md` qui explique ce qui va dedans et sous quelle forme.

## Prérequis

- [Visual Studio Code](https://code.visualstudio.com/)
- Un compte [GitHub](https://github.com/)
- [Git](https://git-scm.com/downloads) — conseillé, mais on peut s'en passer :
  voir « Récupérer le projet » plus bas

Les extensions VS Code ne sont pas à chercher : **le projet les propose
lui-même** à la première ouverture du dossier. Acceptez, elles sont toutes
gratuites.

## Démarrer

### 1. Récupérer le projet

Deux chemins. **Le premier est conseillé, le second est acceptable** — le cours
fonctionne dans les deux cas.

#### Avec Git — conseillé

Depuis la page du dépôt sur GitHub, bouton **Fork** en haut à droite. Vous
obtenez votre propre copie, sur votre compte. Puis, dans un terminal :

```bash
git clone https://github.com/VOTRE-PSEUDO/formation-html.git
```

Ensuite, à chaque fois que vous voulez enregistrer votre avancement :

```bash
git add .
git commit -m "Bloc 03 : la photo et son alt"
git push
```

C'est trois commandes, toujours les mêmes. Et au dernier bloc, publier ne
demandera rien de plus : votre dépôt est déjà en place.

#### Sans Git — si vous n'êtes pas encore à l'aise

Bouton vert **Code** → **Download ZIP**, puis décompressez le dossier où vous
voulez travailler.

Vous perdez l'historique : pas de retour en arrière si vous cassez quelque
chose, et pas de sauvegarde ailleurs que sur votre disque. **Faites des copies
du dossier de temps en temps**, en particulier avant une grosse modification.

Au dernier bloc, vous publierez sans commande, par l'interface de GitHub :

1. Sur GitHub, bouton **+** en haut à droite → **New repository**. Nommez-le,
   cochez **Public**, créez-le.
2. Sur la page du dépôt vide : **uploading an existing file**.
3. Glissez-y le contenu de votre dossier — vos pages, `css/`, `assets/`.
   Les dossiers sont conservés. Validez avec **Commit changes**.
4. **Settings → Pages**, source **Deploy from a branch**, branche `main`,
   dossier `/ (root)`. Enregistrez : l'adresse s'affiche après une minute.

Pour mettre le site à jour ensuite, on repasse par **Add file → Upload files**
et on remplace les fichiers modifiés. C'est là que Git vous manquera : ce
qu'une commande fait en une seconde vous prendra quelques clics à chaque fois.

> Les fichiers `.vscode/` et `.prettierignore` ne servent qu'à votre éditeur.
> S'ils ne montent pas, ça n'a aucune conséquence sur le site en ligne.

### 2. Ouvrir le projet

Dans VS Code : **Fichier → Ouvrir le dossier**, puis choisissez le dossier
`formation-html`.

**Le dossier, pas un fichier.** C'est la seule façon pour que les chemins vers
`css/` et `assets/` se comportent comme prévu, et pour que l'éditeur applique
les réglages du projet.

À la première ouverture, VS Code propose d'installer les extensions
recommandées. Acceptez.

### 3. Voir votre page

L'extension d'aperçu installée avec le projet sert votre site sur un vrai
serveur local et recharge la page à chaque enregistrement.

- Clic droit sur `index.html` → **Open with Live Server**.
- Le site s'ouvre à l'adresse `http://127.0.0.1:5500`.
- Chaque enregistrement recharge la page toute seule : gardez le navigateur
  à côté de l'éditeur.

## Suivi du cours

Les blocs, les exercices et les QCM sont sur la page de parcours :

<!-- À REMPLACER par l'adresse GitHub Pages du parcours -->

**https://…**

Vous y trouverez aussi les deux annexes à garder ouvertes pendant tout le
cours : la référence des balises et les outils.

Votre progression y est enregistrée **dans votre navigateur, sur votre poste**.
Elle ne remonte à personne et elle est perdue si vous changez de machine ou
de navigateur.

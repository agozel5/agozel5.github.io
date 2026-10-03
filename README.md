# Portfolio d'Abdullah Gözel

Site personnel en une seule page (`index.html`), sans serveur ni compilation.

## Mettre en ligne avec GitHub Pages (gratuit, 10 minutes)

1. Sur GitHub, connecté au compte **agozel5**, crée un dépôt public nommé exactement **`agozel5.github.io`**.
2. Dans ce dépôt : **Add file → Upload files**, puis glisse **tout le contenu de ce dossier** (y compris `.nojekyll`). Clique sur **Commit changes**.
3. Va dans **Settings → Pages** et vérifie : *Source* = `Deploy from a branch`, *Branch* = `main` / `root`.
4. Attends 1 à 2 minutes : le site est en ligne sur **https://agozel5.github.io**.

## Ensuite (recommandé)

- **Aperçu LinkedIn** : colle l'adresse dans https://www.linkedin.com/post-inspector/ pour que LinkedIn récupère l'image `og.png`.
- **Google** : déclare le site dans https://search.google.com/search-console (propriété « préfixe d'URL »), puis envoie `sitemap.xml`.
- **Nom de domaine perso** (ex. `abdullahgozel.fr`, environ 10 €/an) : achète-le chez un registraire, ajoute-le dans *Settings → Pages → Custom domain*, puis remplace `https://agozel5.github.io/` par ta nouvelle adresse dans `index.html` (balises `og:image`, `og:url`, `canonical`), `robots.txt` et `sitemap.xml`.

## Contenu du dossier

| Fichier | Rôle |
|---|---|
| `index.html` | le site complet (images intégrées) |
| `og.png` | image d'aperçu pour LinkedIn et les réseaux |
| `Abdullah-Gozel.vcf` | Fiche contact (aussi accessible par le QR code du site) |
| `404.html` | page affichée pour une adresse inexistante |
| `robots.txt`, `sitemap.xml` | référencement |
| `.nojekyll` | indique à GitHub de servir les fichiers tels quels |

Le site charge three.js, GSAP et cannon.js depuis cdnjs.cloudflare.com : une connexion internet est nécessaire pour la 3D (le reste fonctionne sans).


## Formulaire de contact (FormSubmit)

Le formulaire envoie les messages à abdullahgozel@hotmail.com via le service gratuit FormSubmit (formsubmit.co).

1. Une fois le site en ligne, envoie-toi un premier message de test depuis le formulaire.
2. FormSubmit t'envoie alors un email « Action Required: Activate FormSubmit » (vérifie aussi les indésirables). Clique sur « Activate Form ».
3. Les messages suivants arrivent directement dans ta boîte, avec l'adresse du visiteur en « répondre à ».

Si l'envoi échoue, le formulaire propose au visiteur d'écrire depuis sa propre messagerie.

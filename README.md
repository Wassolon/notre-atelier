# Notre atelier

Deux simulateurs industriels autonomes à ouvrir dans un navigateur.

| Fichier | Contenu |
| --- | --- |
| `index.html` | Page d’accueil qui donne accès aux deux ateliers. |
| `Atelier-electrotechnique-V2.html` | Atelier électrotechnique et son code source. |
| `Atelier-electropneumatique.html` | Atelier électropneumatique et son code source. |

Chaque atelier contient son interface HTML, ses styles CSS et sa logique JavaScript dans le même fichier. Dans un éditeur comme VS Code, cherche `<style>` pour les styles et `<script>` pour la logique. Ouvre `index.html` pour utiliser les ateliers en local.

## Conserver le code sur GitHub

1. Décompresse l’archive.
2. Crée un dépôt GitHub nommé `notre-atelier`. Choisis **Private** pour garder le code privé.
3. Dépose le contenu de l’archive à la racine du dépôt, avec `index.html` au même niveau que ce README.
4. Pour une nouvelle version, remplace le fichier concerné et valide le changement par un commit. L’historique de Git permet de retrouver les versions précédentes.

## Mettre le site en ligne

Sur un dépôt éligible à GitHub Pages, ouvre **Settings → Pages → Deploy from a branch**, sélectionne **main** et **/(root)**, puis enregistre. GitHub affichera l’adresse du site dans **Settings → Pages**. Vérifie la visibilité du site avant d’y mettre du contenu personnel.

[Documentation GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)

## Sauvegarder les montages

Garde les fichiers JSON de tes montages séparément. Tu peux les importer dans l’atelier correspondant, sur ton PC ou sur le site. L’hébergement statique sert le simulateur. Une synchronisation des montages entre appareils nécessiterait un stockage partagé à développer.

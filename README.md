# RP Narratif Naruto Legacy — Wiki

Ce dossier contient la première base du wiki public Naruto Legacy.

## Modifier les pages

Les articles se trouvent dans `docs/`. Ils sont écrits en Markdown :
- `# Titre` crée un titre
- `## Sous-titre` crée un sous-titre
- `**texte**` met du texte en gras
- `- élément` crée une liste
- `[Nom de la page](../dossier/page.md)` crée un lien

Tu peux modifier les fichiers `.md` directement depuis GitHub : ouvre le fichier, clique sur le crayon, modifie le texte puis valide avec **Commit changes**.

## Publier gratuitement avec GitHub Pages

1. Crée un compte sur https://github.com/ si nécessaire.
2. Crée un dépôt nommé `naruto-legacy-wiki` et choisis **Public**.
3. Envoie tous les fichiers de ce dossier dans le dépôt, en conservant les dossiers `.github` et `docs`.
4. Dans `mkdocs.yml`, remplace `VOTRE-PSEUDO` par ton identifiant GitHub dans `site_url`.
5. Dans GitHub : **Settings → Pages**. Choisis **Deploy from a branch**, puis la branche `gh-pages` et le dossier `/ (root)`.
6. Dans l'onglet **Actions**, attends la fin du workflow de publication.

L'adresse sera de la forme :
`https://TON-PSEUDO.github.io/naruto-legacy-wiki/`

Chaque modification envoyée sur `main` déclenchera une nouvelle publication.

## Important

- Le dépôt étant public, les fichiers sources sont publics eux aussi.
- N'ajoute aucune information privée ou réservée au staff.
- Le contenu des pages est volontairement laissé à compléter : aucun élément de lore n'a été inventé.
- Pour changer le menu, modifie la section `nav` de `mkdocs.yml`.

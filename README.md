# Yboost

Site CV personnel d'Amine Habily, realise en HTML et CSS avec Bootstrap.

## Contenu

- Presentation et parcours
- Competences techniques et soft skills
- Projets avec liens vers GitHub
- Coordonnees de contact

## Technologies

- HTML5
- CSS3
- Bootstrap 5.3

## Lancer le site en local

Le site ne necessite aucune compilation. Ouvrez `index.html` dans un navigateur, ou lancez un serveur local depuis la racine du depot :

```sh
python3 -m http.server 8000
```

Ouvrez ensuite <http://localhost:8000>.

## Deploiement sur GitHub Pages

Le workflow `.github/workflows/pages.yml` publie automatiquement le site sur GitHub Pages a chaque push sur la branche `main`. Il peut aussi etre lance manuellement depuis l'onglet **Actions** avec **Run workflow**.

Pour activer Pages la premiere fois :

1. Ouvrez **Settings > Pages** dans le depot GitHub.
2. Dans **Build and deployment**, choisissez **GitHub Actions** comme source.
3. Poussez vos changements sur `main`. Suivez l'execution dans l'onglet **Actions**.

Apres le deploiement, le site est accessible a l'adresse <https://amine3060.github.io/yboost/>.

## Structure

```text
.
|-- .github/workflows/pages.yml  # Deploiement GitHub Pages
|-- index.html                   # Contenu du site
|-- style.css                    # Styles personnalises
`-- README.md                    # Documentation
```
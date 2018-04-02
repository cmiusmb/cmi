# Site Web CMI USMB

## Un tutorial markdown

[https://guides.github.com/features/mastering-markdown/](https://guides.github.com/features/mastering-markdown/)

## Un tutoriel pour le thème minimal-mistakes de Jekyll

[https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/](https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/)

## Ajouter une page

aller dans `_pages` et créer un nouveau fichier, par exemple `toto.md` avec comme en-tête

```markdown
---
layout: single
permalink: /toto
---
```

La ligne `permalink:: /toto` indique que la page décrite par `toto.md` sera accessible via l'url `http://monsite/toto`

Si on veut ajouter une entrée dans la list des onglets pour la page toto, il suffit d'ajouter l'entrée suivante dans la section `main:` du fichier `_data/navigation.yml`

```yaml
  - title: Ma page toto
    url: /toto
```
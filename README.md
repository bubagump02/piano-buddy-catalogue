# Catalogue de départ de Piano Buddy

Des morceaux de piano du domaine public, en MIDI, que le lecteur de Piano Buddy propose quand aucune partition n'est ouverte. Le lecteur les lit par jsdelivr, à un commit figé de ce dépôt.

- `catalogue.json` : la fiche de chaque morceau (titre, compositeur, niveau, gravure, page Mutopia).
- `*.mid` : une piste par main, la levée écrite comme une courte mesure avant la vraie.

## Licence

Chaque fichier vient d'une gravure du [Mutopia Project](https://www.mutopiaproject.org) placée dans le domaine public par son graveur, d'une œuvre elle-même du domaine public. La fiche de chaque morceau nomme le graveur et donne la page Mutopia.

## Fabrication

Ne pas modifier à la main : ces fichiers sont produits par `outils/catalogue.py` du dépôt de l'app, qui vérifie la licence de chaque source.

# pandochceres

HCERES style pour pandoc.

Permet de générer un pdf dans le format attendu par l'[HCERES](http://www.hceres.fr)
en utilisant comme source du texte au format markdown (et du latex)
et en utilisant [pandoc](http://pandoc.org) pour obtenir un pdf.

## Comment l'utiliser

Pour générer le document en conservant les instructions, utiliser la commande suivante :

`pandoc --template hceres.latex.format trame_dae_ur_fr.md -o trame_dae_ur_fr.pdf`

Pour enlever les instructions, utiliser la commande suivante :

`pandoc -V noinstructions --template hceres.latex.format trame_dae_ur_fr.md -o trame_dae_ur_fr.pdf`

## Pour les utilisateurs de latex

Le style latex pour pandoc permet de générer un fichier latex complet à l'aide de la commande suivante :

```
pandoc -r markdown-auto_identifiers --template hceres.latex.format trame_dae_ur_fr.md -s -o trame_dae_ur_fr.tex
```

Le fichier latex est disponible dans le dépôt pour permettre sa réutilisation sans avoir pandoc.

## Contributions bienvenues

Le fichier de style correspond globalement à ce qui est attendu.

Commentaires, suggestions d'amélioration et contributions sont les bienvenues.

# pandochceres

HCERES style pour pandoc.

Permet de générer un pdf dans le format attendu par l'HCERES
en utilisant comme source du texte au format markdown (et du latex)
et en utilisant pandoc pour obtenir un pdf.

## Comment l'utiliser

`pandoc --pdf-engine=xelatex --template hceres.latex.format example.md -o example.pdf`

## Contributions bienvenues

Le fichier de style correspond globalement à ce qui est attendu.

Commentaires, suggestions d'amélioration et contributions bienvenues.

# anima-sheet-img

Images d'une fiche de personnage Roll20 personnalisée pour Anima Beyond Fantasy, servies via jsDelivr :
`https://cdn.jsdelivr.net/gh/MrPanda88/anima-sheet-img@main/img/<fichier>`.

- `icon-NN.svg` : icônes SVG du thème « Grimoire ». Dessins originaux, libres d'utilisation (licence CC0).
- `arcana-bg.jpg` : fond de l'arbre Arcana.
- `img-<empreinte>.<ext>` : fonds et bordures du thème « Livre » et du choix de thème de la fiche (fond Gaia,
  parchemin Prometheum, glyphes de l'Arcana Exxet, cadres et ornements). Le nom est une empreinte du contenu :
  une image modifiée devient un nouveau fichier, les anciennes adresses restent valides.

Les noms et les fichiers sont produits par l'export de la fiche (`node build.mjs --roll20 --img-base …`, dossier `export/img/`).

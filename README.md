# 200223_Bouton-poussoir-HTML-CSS-only
 
Bienvenu ! Dans ce tutoriel, je vous propose de créer un bouton avec effet poussoir.

Le principe est simple : on commence avec un lien que l'on met en forme de bouton (un rectangle par exemple). Pour donner un effet 3D, il suffit de placer une ombre sous ce rectangle avec la propriété "box-shadow". 
Cette propriété prend plusieurs paramètres : le décalage selon l'axe horizontal, le décalage selon l'axe vertical, le flou, et la couleur.
Pour en savoir plus : https://developer.mozilla.org/fr/docs/Web/CSS/box-shadow
Ici, l'ombre est exactement sous l'élément, et sans flou, afin de donner l'impression d'une continuité de notre élément lien. Ceci donne un effet de bouton 3D.

Au moment du clic (état :active) notre bouton doit donner l'impression de s'enfoncer. Pour ce faire, deux étapes : 
1) décaler le bouton de X pixels vers le bas
2) Réduire la taille de l'ombre de X pixels pour compenser

De cette façon, on a vraiment l'impression de voir un bouton qui s'enfonce !
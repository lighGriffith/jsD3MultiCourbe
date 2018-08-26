# D3.js curve exemple

Ce projet a été conçu pour comparer une courbe(ou plusieurs) à un ensemble d'autres courbes.
La(ou les) courbe(s) que l'on veut comparer sont des fichiers .dat à ajouter dans datas.
Les courbes de comparaison sont regroupées dans un fichier excel(comparaison générale).

Dans l'exemple considéré, le problème était de pouvoir comparer une mesure expérimentale de diffraction I=f(θ) avec un ensemble d'autre mesure I=f(θ) afin de déterminer quelles étaient la structure de la maille et les éléments impurs présents dans un matériau.

## Comment l'utiliser

1. Se placer dans le dossier datas et lancer python simple-cors-http-server.py afin de pouvoir transmettre les fichiers au navigateur en évitant les problèmes de cross-domain.
2. click droit sur index.html et ouvrir dans le navigateur.


### Remarques

Les courbes à comparer doivent être ajoutées sous forme de fichier .dat sans espace dans le nom, être placées dans datas et être du type :
xDebut    pas   xFin    valeur[0]    valeur[1] .... valeur[n]

Les courbes théoriques doivent être de la même longeur avec la première colone correspondant à l'angle.




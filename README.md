# Audio Pad

## Pitch

Le but est de réaliser une boîte à rythme / sampler en JavaScript en utilisant des samples en MP3.

## Tâches à effectuer

- Le sample doit réagir au click **et** avec les touches du clavier.
- Lors de l'activation d'un bouton, celui-ci doit passer au vert (voir CSS) un court instant et puis s'éteindre / revenir à son état original.
- Les sons se trouvent dans le dossier sounds, vous pouvez les changer si vous le désirez.
- Chaque `div.button` possède 2 attributs data: `data-key` indique avec quelle touche clavier déclencher le bouton et `data-sound` n'indique pas le nom du fichier MP3 **mais une _sorte_ de son**. Il faut donc faire la correspondance entre ce nom et le fichier sonore que vous voulez lui attacher.

## Points importants

- Pensez à rendre votre code **générique** grâce à l'utilisation d'objets et de fonctions
- Vous pouvez utiliser la librairie [howler.js](http://goldfirestudios.com/blog/104/howler.js-Modern-Web-Audio-Javascript-Library) pour vous faciliter la prise en main des sons

** Drop the beat !**
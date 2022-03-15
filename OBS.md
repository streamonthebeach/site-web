---
layout: default
title: "OBS"
---
# STREAM On The Beach

## Tuotoriel OBS - Open Broadcast Software

### OBS, qu’est-ce que c’est ?

C’est un logiciel gratuit et open-source, qui permet l’enregistrement et la diffusion de vidéos.

## I - Interface OBS

A l’ouverture du logiciel, la fenêtre suivante s’ouvre :

![image](/resources/OBS1.JPG)

Cette fenêtre est divisée en plusieurs interfaces, chacune avec sa propre fonction.

![image](/resources/OBS2.JPG)

Avant de détailler leurs fonctions, il faut comprendre comment OBS fonctionne. Lors d’un enregistrement/diffusion live, c’est l’écran de l’interface principale qui est montré. Il est possible de créer de multiples écrans différents appelés scènes, et de passer de l’une à l’autre durant l’enregistrement. Les éléments composants chaque scène sont appelés sources. Une source peut être : une image, une vidéo, une webcam, mais également un audio, un micro !
La possibilité de passer d’une scène à une autre durant un enregistrement implique la présence de transitions, entièrement personnalisables pour passer d’une scène à une autre.

Interface scènes :

![image](/resources/OBS3.JPG)

C’est ici que l’on retrouve la liste des scènes.

- Pour ajouter une scène, il suffit de cliquer sur le bouton “+” , une fenêtre s’ouvre alors et vous permet de nommer la nouvelle scène.
- Pour supprimer une scène : bouton “-”
- Pour modifier l’ordre de présentation des scènes : boutons “/\” et ” \/ ”

Interface sources :

C’est l’interface la plus importante car c’est elle qui permet de personnaliser les différentes scènes.

![image](/resources/OBS4.JPG)

- Bouton + : rajouter une nouvelle source
- Bouton - : supprimer une source existante
- Bouton paramètres : lorsqu’une source est sélectionnée, ce - - - Bouton permet d’ouvrir son menu de propriétés
- Bouton /\ et \/ (ou drag and drop depuis la liste des sources) : modifier l’ordre des sources. La source située tout en haut de la liste sera celle le plus au premier plan, à l’inverse une source en bas de cette liste sera en arrière plan par rapport aux autres.

En appuyant sur le bouton + il est possible de sélectionner le type de source à ajouter parmi un large choix.

Sources disponibles :

![image](/resources/OBS5.JPG)

Capture audio (entrée) : permet de récupérer l’audio depuis n’importe quel périphérique, micro intégré à l’ordinateur, aux caméras ou au micro branché sur les caméras.

Capture audio (sortie) : permet de gérer l’audio sortant (par défaut, tous les sons sortants de l’ordinateur)

Capture d’écran : permet de capturer l’écran complet depuis l’ordinateur principal

Capture de jeu (client syphon):

Capture de fenêtre : permet de capturer une fenêtre en particulier depuis l’ordinateur principal

Diaporama : il suffit d’ajouter les fichiers images que l’on souhaite voir en diaporama, les transitions se font automatiquement et il est possible de régler la vitesse de défilement

Image : ajout d’un fichier image au choix

Navigateur : partage d’écran du navigateur utilisé

Périphérique de capture vidéo : permet d’afficher l’entrée image depuis un périphérique connecté à l’ordinateur principal : caméra, webcam intégrée.

Scène : permet d’ajouter une scène complète dans une autre.

Utile par exemple pour utiliser le fond vert.

Source de couleur : fond coloré, couleur au choix

Source média : permet la lecture d’une vidéo locale, en boucle ou non.

Source vidéo VLC : permet la lecture d’une vidéo

Texte : ajout texte, police, taille et couleur au choix

Groupe : Insérer un groupe de sources déjà configuré au préalable.

Une fois la source ajoutée, il est possible de la déplacer et de modifier sa taille depuis l’interface principale.

Boutons propriétés et filtres :

![image](/resources/OBS6.JPG)

Lorsqu’une source est sélectionnée, les boutons "Propriétés” et “Filtres” deviennent cliquables. Le bouton “Propriétés” permet de ré-ouvrir le menu

Les Filtres :

![image](/resources/OBS7.JPG)

Il est possible d’ajouter de nombreux filtres sur vos sources vidéos mais aussi audios !

Filtres d’effet :

- Accentuer : modification de la netteté
- Appliquer un LUT :(Look-Up Tables)  effet de filtres (sépia, N&B, pseudo infrarouge etc…) De nombreux filtres sont téléchargeables gratuitement sur le web pour trouver un filtre que correspondra à vos envies !
- Corrections colorimétriques : permet la correction de nombreux paramètres de l’image : gamme, contraste, luminosité, saturation, décalage de teinte, opacité
- Défilement : ajout d'un défilement de l’image (vertical, horizontal ou les deux!)
- Délai de rendu : ajout d’un retard au choix
- Incrustation par chrominance (Chroma Key) : à utiliser pour le fond vert ! Permet d’effacer une partie de l’image en fonction de sa couleur : vert / bleu / magenta ou custom (on utilisera le vert)
- Incrustation par couleur : similaire à l’incrustation Chroma - - Key pour utiliser un fond vert, mais privilégiez plutôt Chroma Key
- Incrustation par luminance (Luma Key) : utilisé pour effacer une partie de l’image, mais en se basant sur la luminance et non la couleur.
- Masque d’image/mélange
- Mise à l’échelle/ Rapport d’affichage
- Rogner/Encadrer : permet de rogner l’image. A noter qu’il est possible de rogner une source depuis l’interface graphique directement en maintenant Alt et en déplaçant les bords rouges de la source (ils deviendront verts d’ailleurs)

Filtres d’effet audios :

![image](/resources/OBS8.JPG)

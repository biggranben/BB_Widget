# Widgets pour Jeedom

## BB_ToggleSwitch_CSS

--> <a href="https://github.com/biggranben/BB_Widget/blob/main/dashboard/cmd.action.other.BB_ToggleSwitch_CSS.html">cmd.action.other.BB_ToggleSwitch_CSS.html</a>

Bouton simple type Toggle Switch en CSS :

![Alt text](doc/images/BB_ToggleSwitch_CSS_on.jpg?raw=true "ON")
![Alt text](doc/images/BB_ToggleSwitch_CSS_off.jpg?raw=true "OFF")

Presque entièrement personnalisable (sauf les icones pour le moment) :

![Alt text](doc/images/BB_ToggleSwitch_CSS_orange.jpg?raw=true "Orange")

![Alt text](doc/images/BB_ToggleSwitch_CSS_persoON.jpg?raw=true "Perso ON")
![Alt text](doc/images/BB_ToggleSwitch_CSS_persoOFF.jpg?raw=true "Perso OFF")

### Options paramétrables dans "Paramètres optionnels widget" :
*(appliquez bien les mêmes paramètres sur les commandes ON et OFF)*

- colorON : couleur de la puce, tout code couleur accepté par background en CSS (mots clés ou hexa)
- colorONback : personnalisable ou par défaut 30% plus sombre que colorON
- colorOFF : idem ON
- colorOFFback : idem ONback
- width : largeur, par défaut : 50px
- height : hauteur, par défaut : 20px
- margin : delta entre la hauteur du widget et la taille du bouton (défini la taille du cercle), par défaut : 4px
- logoON : non fonctionnel, objectif pouvoir changer l'icone ON
- logoOFF : non fonctionnel, objectif pouvoir changer l'icone OFF

![Alt text](doc/images/BB_ToggleSwitch_CSS_perso.jpg?raw=true "Param")

## BB_ToggleSwitch_CSS2

--> <a href="https://github.com/biggranben/BB_Widget/blob/main/dashboard/cmd.action.other.BB_ToggleSwitch_CSS2.html">cmd.action.other.BB_ToggleSwitch_CSS2.html</a>

Bouton simple type Toggle Switch avec Texte en CSS :

![Alt text](doc/images/BB_ToggleSwitch_CSS2_on.jpg?raw=true "ON")
![Alt text](doc/images/BB_ToggleSwitch_CSS2_off.jpg?raw=true "OFF")

Presque entièrement personnalisable :

![Alt text](doc/images/BB_ToggleSwitch_CSS2_persoON.jpg?raw=true "Perso ON")
![Alt text](doc/images/BB_ToggleSwitch_CSS2_persoOFF.jpg?raw=true "Perso OFF")

### Options paramétrables dans "Paramètres optionnels widget" :
*(appliquez bien les mêmes paramètres sur les commandes ON et OFF)*

- colorON : couleur du fond, tout code couleur accepté par background en CSS (mots clés ou hexa)
- colorTextON : couleur du texte ON
- textON : texte du bouton en remplacement de ON
- colorOFF : idem ON
- colorTextOFF : idem ON
- textOFF : idem ON
- width : largeur, par défaut : 55px
- height : hauteur, par défaut : 18px
- border : taille de la bordure du bouton, par défaut : 1px
- gradient : couleur du gradient pour le bouton et le contour, par défaut : #e1e1e1

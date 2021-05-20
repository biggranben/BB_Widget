# Widgets pour Jeedom

## cmd.action.other.BB_ToggleSwitch_CSS.html

Bouton simple type Toggle Switch en CSS :

![Alt text](doc/images/BB_ToggleSwitch_CSS_on.jpg?raw=true "ON")
![Alt text](doc/images/BB_ToggleSwitch_CSS_off.jpg?raw=true "OFF")

Presque entièrement personnalisable (sauf les icones pour le moment) :

![Alt text](doc/images/BB_ToggleSwitch_CSS_orange.jpg?raw=true "Orange")

![Alt text](doc/images/BB_ToggleSwitch_CSS_persoON.jpg?raw=true "Perso ON")
![Alt text](doc/images/BB_ToggleSwitch_CSS_persoOFF.jpg?raw=true "Perso OFF")

### Options paramétrables dans "Paramètres optionnels widget" :
*(appliquez bien les mêmes paramètres sur les commandes ON et OFF)*

- colorON : tout code couleur accepté par background en CSS (mots clés ou hexa)
- colorONback : personnalisable ou par défaut 30% plus sombre que colorON
- colorOFF : idem ON
- colorOFFback : idem ONback
- width : largeur, par défaut : 50px
- height : hauteur, par défaut : 20px
- margin : delta entre la hauteur du widget et la taille du bouton (défini la taille du cercle), par défaut : 4px
- logoON : non fonctionnel, objectif pouvoir changer l'icone ON
- logoOFF : non fonctionnel, objectif pouvoir changer l'icone OFF

![Alt text](doc/images/BB_ToggleSwitch_CSS_perso.jpg?raw=true "Param")
